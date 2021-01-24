# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

!!! note
    Simple note


!!! note "Please note:"
    To use notes you must add 'admonition'
    to the markdown extensions in mkdocs.yml:<br/>
    > `markdown_extensions:`<br/>
    `     - admonition`
    
    <code>Code Block<br />
    Line2</code>

!!! note ""
    Simple note without title.

!!! seealso
    seealso note

!!! abstract
    abstract note

!!! summary
    summary note

!!! tldr
    tldr note

!!! info
    info note

!!! todo
    todo note

!!! tip
    tip note

!!! hint
    hint note

!!! important
    important note

!!! success
    success note

!!! check
    check note

!!! done
    done note

!!! question
    question note

!!! help
    help note

!!! faq
    faq note

!!! warning
    warning note

!!! caution
    caution note

!!! attention
    attention note

!!! failure
    failure note

!!! fail
    fail note

!!! missing
    missing note

!!! danger
    danger note

!!! error
    error note

!!! bug
    bug note

!!! example
    example note

!!! snippet
    snippet note

!!! quote
    quote note

!!! cite
    cite note



Code:

``` hl_lines="3 4"
Fenced code blocks are like Standard
Markdown’s regular code blocks, except that
they’re not indented and instead rely on
start and end fence lines to delimit the
code block.
```

Python Code:

```python
def fn():
    pass
```

Wonkey Code:

```monkey hl_lines="2"
Function Main:Void()
    Print "Hello World!"
End
```


Inline ==code==: `#!monkey Function Main()`

* [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
* [x] Nulla lobortis egestas semper
* [x] Curabitur elit nibh, euismod et ullamcorper at, iaculis feugiat est
* [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [x] Sed egestas felis quis elit dapibus, ac aliquet turpis mattis
    * [ ] Praesent sed risus massa
* [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
* [ ] Nulla vel eros venenatis, imperdiet enim id, faucibus nisi
* [ ] ~~Strikethrough text~~
