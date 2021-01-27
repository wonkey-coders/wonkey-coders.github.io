_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).New_
##### Method New:Void( length:[Int](../../modules/wonkey/wonkey-types-int.md),byteOrder:[ByteOrder](../../modules/std/std-memory-byteorder.md)=std.memory.ByteOrder.LittleEndian )
##### Method New:Void( data:Void Ptr,length:[Int](../../modules/wonkey/wonkey-types-int.md),byteOrder:[ByteOrder](../../modules/std/std-memory-byteorder.md)=std.memory.ByteOrder.LittleEndian )
Creates a new data buffer.

Creates a data buffer with a newly allocated or existing block of memory.

If you provide a `start` pointer value when creating a data buffer, it should point to a valid block of memory at least `length` bytes in size.
This pointer value will be used as the 'base address' when poking/peeking the data buffer, and will be returned by the [Data](std-memory-databuffer-data.md) property.
Such data buffer cannot be [Resize](std-memory-databuffer-resize.md)d.

If you do not provide a `start` value, a block of memory `length` bytes long is allocated for you. This memory will be released when the data
buffer is discarded or becomes unreachable by the garbage collector.

The new databuffer initally uses little endian byte order. You can change this via the ByteOrder property.

When you have finished with the data buffer, you should call its inherited [Resource.Discard](std-memory-databuffer-resource.discard.md) method.

```

	\#Import "<std>"

	Using std.memory

	Function Main()

		Local buf:=New DataBuffer( 10 )

		Print buf.Length

		For Local i:=0 Until 10
			buf.PokeByte( i,i*2 )
		Next

		For Local i:=0 Until 10
			Print buf.PeekByte( i )
		Next

	End

```

| Parameters |    |
|:-----------|:---|
| `start` | start The start of the data buffer memory. |
| `length` | length The length of the data buffer memory in bytes. |
| `byteOrder` | byteOrder Initial byte order of the data. |
