# plaintext_tools_expo
Showcases plaintext visualization tools that I find useful

| name | input | output | comment |
|------|-------|--------|---------|
| asciigraph | plaintext | plaintext | |
| gaf | plaintext | plaintext (UTF8) | budget|
| graph-easy | plaintext | plaintext | |
| csvkit | plaintext | plaintext| |
| tree | (state) | plaintext | |
| text-diagram |  plaintext | plaintext | uml |
| adia | plaintext | plaintext | uml |
| qsde | | graphics | |
| plantuml | | graphics| |
| graphviz | | graphics | |
| yEd | | graphics | |
| mermaid |  | graphics | |
| d2 | plaintext | graphics | |

See also:
* Diagramming: `cli_tool_input_output_plaintext_tools_expo.overleaf.pdf`
* Markup: `pandoc_plaintext_markup_formats_expo.pdf`

### Not to be confused with
lightweight markup languages
* toml
* org-mode
* setext
* Markup: `pandoc_plaintext_markup_formats_expo.pdf`
Tools
* pandoc


### asciigraph

https://github.com/zyona3/gaf

```
  10.00 ┤        ╭╮
   9.00 ┤ ╭╮     ││
   8.00 ┤ ││   ╭╮││
   7.00 ┤ ││   ││││╭╮
   6.00 ┤ │╰╮  ││││││ ╭
   5.00 ┤ │ │ ╭╯╰╯│││╭╯
   4.00 ┤╭╯ │╭╯   ││││
   3.00 ┼╯  ││    ││││
   2.00 ┤   ╰╯    ╰╯╰╯
```


### gaf
https://github.com/Xx0w0wxX/gaf
```
    python :  █████████████████████▎
        go :  ██████
   flutter :  ███████████████████
javascript :  ████████████████████████████████▎
      html :  ███████████████████▎
       css :  ███████████████████▋
       php :  ████████████████████████▋
```
### grapheasy

```
= plaintext tools =

* csvkit
* tree (unix)

== Diagramming ==

=== text input, text output ===

* asciigraph (github)
* graph-easy (github)
* UML sequence diagram: https://github.com/weidagang/text-diagram (I wish this was ported to a CLI tool)
** More suggestions at: https://textart.io/sequence

=== text input, graphic output ===

* qsde
* plantuml
* graphviz
* yEd (it’s still stored as plaintext)
```
```
=== Plaintext tools for 2D visuallization (toolbelt) ===
#productivity 
2021-08-11
 
==== Text to text ====
 
tree (unix)
asciigraph (github)
graph-easy (github)
UML sequence diagram: https://github.com/weidagang/text-diagram (I wish this was ported to a CLI tool)
 
2021-08-11
 
==== Text to graphics ====
qsde
plantuml
graphviz
 
yEd (it's still stored as plaintext)
mermaid
 
More suggestions at:
https://textart.io/sequence
 
2021-08-11
```


### Others


* vd (visidata)
* `plot` in terminal (GNU Plot, not to be confused with the R gplot package)
* `tsort` - 2024-09-18: show sample input and output (check wikipedia)
* xml tools
   * `pandoc` to strip html
* conversion tools
   * `yq`, `xq` and `jq`
   * `m4`


#### boxes
2024

* https://github.com/ascii-boxes/boxes

```
brew install boxes
boxes -l
```
* https://github.com/sarnobat/plaintext_tools_expo/blob/main/boxes.md

#### as-tree
https://github.com/jez/as-tree

* may not need path2indented.py anymore

#### astree

https://github.com/yzhong52/ascii_tree


Input: markdown headings
```
             ┌──────┐
             │ Root │
             └──┬───┘
           ┌────┴────┐
           │ Child 1 │
           └────┬────┘
       ┌────────┴────────┐
┌──────┴───────┐  ┌──────┴───────┐
│ Grandchild 1 │  │ Grandchild 2 │
└──────────────┘  └──────────────┘
```

#### adia

```
 DIAGRAM: Foo                             

 +-----+             +-----+
 | foo |             | bar |
 +-----+             +-----+
    |                   |
    |~~~Hello World!~~~>|
    |                   |
    |<------------------|
    |                   |
 +-----+             +-----+
 | foo |             | bar |
 +-----+             +-----+
```
2024-10-21
https://github.com/pylover/adia

#### groff

It can create plaintext output (diagrams too)
`troff_examples.sh`
`cat ~/src.git/troff/plaintext.out.txt`
