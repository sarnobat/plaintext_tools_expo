# plaintext_tools_expo
Showcases plaintext visualization tools that I find useful

| name | input | output | comment |
|------|-------|--------|---------|
| asciigraph | plaintext | plaintext | |
| gaf | plaintext | plaintext (UTF8) | |
| graph-easy | plaintext | plaintext | |
| csvkit | plaintext | plaintext| |
| tree | (state) | plaintext | |
| text-diagram | | plaintext | |
| qsde | | graphics | |
| plantuml | | graphics| |
| graphviz | | graphics | |
| yEd | | graphics | |
| mermaid |  | graphics | |


### asciigraph


### gaf
https://github.com/Xx0w0wxX/gaf

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
