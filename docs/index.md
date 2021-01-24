![Banner](images/banner.png)

# Welcome to Wonkey!

* Wonkey is an open-source cross-platform programming language.

* Wonkey is a fork of the Monkey2 programming language, developed by Mark Sibly, creator of the ‘Blitz’ range of languages (BlitzBasic, Blitz2D, Blitz3D, BlitzPlus, BlitzMax).

[^comment]: # (designed primarily for game programming.)

[^comment]: # (The monkey2 release includes a simple IDE coded in pure monkey2 called 'Ted2'. Ted2 is not a fully fledged IDE (yet) but is intended to provide a 'works anywhere' IDE solution for using monkey2 on any platform you can get it building on.)

* Wonkey is a community project.

* Wonkey offers some very powerful new features including:

	* Function overloading

		Functions with the same name can have different parameter types.

		```monkey
		Function Add( a:Int, b:Int )
			Return a + b
		End

		Function Add( a:Float, b:Float )
			Return a + b
		End
		```

	* 'First class' functions

		Functions (and methods) can be stored in variables and passed to/from other functions.

		```monkey
		Function Test1()
			Print "Test1!"
		End

		Function Test2()
			Print "Test2!"
		End

		Function Tester( test:Void() )
			test()
		End

		Function Main()
			Tester( Test1 )
			Tester( Test2 )
		End
		```

	* Lambda functions

		Lambda functions allow you to create closures:

		```monkey
		Function Test( func:Void() )
			func()
		End

		Function Main()
			For Local i:=0 Until 10
				Test( Lambda()
						Print i
				      End )
			Next
		End
		```

[^comment]: # (## Generic classes and methods)

    * Templates / Generics

        Classes, interfaces, structs, methods and functions can have ‘type’ parameters:

        ```monkey
        Struct Rect<T>
            Field x:T
            Field y:T
            Field width:T
            Field height:T
        End

        Function Main()
            Local r := New Rect<Float>
        End
        ```

[^comment]: # (## New 'Struct' type that provides value semantics)

    * Structs

        Structs are similar to classes in that they encapsulate member data, but differ in that they are passed around ‘by value’ instead of ‘by reference’.

        This allows structs to be efficiently created on the stack without any garbage collection overhead.

        ```monkey
        Struct S
            Field data:Int=10
        End

        Function Test( s:S )
            s.data = 100
        End

        Function Main()
            Local s := New S  ' Create a new S on the stack (very fast!)
            Test( s )         ' Test gets a copy of 's'.
            Print s.data      ' Print '10'
        End
        ```

[^comment]: # (## Fibers for easy asynchronous programming.)

    * Fibers

        Fibers provide support for ‘cooperative’ multithreading:

        ```monkey
        Function Server( host:String,service:String )
            Local server:=Socket.Listen( host,service )

            Repeat
                Local client:=server.Accept()

                New Fiber( Lambda()
                    Local data:=client.Receive(...)
                End )
            Forever
        End
        ```

    * Operator overloading

        Operator overloading allows you to override the meaning of the built-in language operators, making for more expressive code:

        ```monkey
        Struct Vec2
            Field x:Float
            Field y:Float

            Method New( x:float,y:Float )
                Self.x=x
                Self.y=y
            End

            Operator+:Vec2( v:Vec2 )
                Return New Vec2( x+v.x,y+v.y )
            End

            Operator To:String()
                Return "Vec2("+x+","+y+")"
            End

        End

        Function Main()
            Local v0 := New Vec2( 10,20 )
            Local v1 := New Vec2( 30,40 )

            Print v0+v1
        End
        ```

    * Optional reflection features

        Wonkey includes an optional reflection system that allows you to inspect and modify variables and values at runtime:

        ```monkey
        #Import "<reflection>"

        Class C
            Method Update( msg:String )
                Print "C.Update : msg="+msg
            End
        End

        Function Main()
            Local c:=New C

            Local type := Typeof( c )
            Print type

            Local decl:=type.GetDecl( "Update" )
            decl.Invoke( c,"Hello World!" )
        End
        ```

    * Class extensions

        Class extensions allow you to add extra methods and functions to existing classes.

    * Fully garbage collected

        Wonkey provides a ‘mostly’ incremental garbage collector that efficiently collects garbage as it runs without any of those annoying ‘sweep’ spikes found in typical garbage collectors.

<!---
<table class="codehilitetable">
<tr>
<td class="linenos">
<div class="linenodiv">
<pre>
<span></span>
 1
 2
 3
 4
 5
 6
 7
 8
 9
10
</pre>
</div>
</td>
 
<td class="code"><div class="codehilite"><pre><span></span><span class="nf">Struct</span> <span class="nf">Rect</span><span class="o">&lt;</span><span class="no">T</span><span class="o">&gt;</span>
    <span class="kd">Field</span> <span class="nv">x</span><span class="p">:</span><span class="nc">T</span>
    <span class="kd">Field</span> <span class="nv">y</span><span class="p">:</span><span class="nc">T</span>
    <span class="kd">Field</span> <span class="nv">width</span><span class="p">:</span><span class="nc">T</span>
    <span class="kd">Field</span> <span class="nv">height</span><span class="p">:</span><span class="nc">T</span>
<span class="kr">End</span>

<span class="kr">Function</span> <span class="nf">Main</span><span class="p">()</span>
    <span class="kd">Local</span> <span class="nv">r</span> <span class="p">:</span><span class="o">=</span> <span class="kr">New</span> <span class="nc">Rect</span><span class="p">&lt;</span><span class="kt">Float</span><span class="p">&gt;</span>
<span class="kr">End</span>
</pre></div>
</td></tr></table>
-->
