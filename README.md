# Table of content

[Basic options](#Basic-options)  
[Search field terminator](#Search-field-terminator)  
[Very userful time saver](#Very-userful-time-saver)  
[Pattern indise a pattern](#Pattern-indise-a-pattern)  
[Bonus](#Bonus)

### Basic options

*Ignore case*
```bash
:h /\c
:h /\C
```

*Magic search*

```bash
:h /\v
:h /\V
```

*Search forward and backward for the [count]'th occurrence of the word nearest to the cursor*

```bash
:h *star
:h #
```

*Working with registers*

```bash
:h quote_alpha
```

Paste from buffer:
1) Insert mode: `<C-r>{register}`
2) Normal mode: `"{register}p`


*Expression register*

```bash
:h quote_=
```

*Substitute*

```bash
:h :Substitute
```

### Search field terminator

Example with url

To try:  
    `/<C-r>=escape(<pattern>, getcmdtype())`

https://github.com/HeySlava/vim_search_and_replace


### Very userful time saver

`:help CTRL-R_CTRL-W`

[Example with long func name](./example_with_very_long_name)


### Pattern indise a pattern

```bash
:h /\zs
:h /\ze
```

[Example with sqlalchemy](./example_with_sa)



### Bonus

```bash
:h :&
```

`:s///gn`


```bash
:h :global
```
`g/TODO/`
