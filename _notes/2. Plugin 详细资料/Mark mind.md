---
Tag: Reference

Type: Tool

Info: [Obsidian mark mind]

Num: 11
---


# Github
>[! info] https://github.com/MarkMindCkm/obsidian-markmind

---


# Obsidian mark mind

[中文手册](https://github.com/MarkMindCkm/obsidian-markmind/blob/main/docs/%E7%94%A8%E6%88%B7%E6%89%8B%E5%86%8C.md)

## Notice

This is not an open source project . but `lishid (obsidian developer)` can check this code.  
Web site : [https://www.markmind.net](https://www.markmind.net/)

### Price

free

Catalyst

`basic` mode of mindmap

advanced features in `rich` mode of mind map

most features in `rich` mode of mindmap

pdf annotate

list mode

support development

support mobile and pc

support mobile and pc

$0

$12 （forever）

[Buy](https://www.markmind.net/)

You can try it for 30 days for free，and you can buy a active code in website , then input it in setting tab

---

## Markmind docs navigation

### Mindmap

-   [Create basic mode of mindmap](https://markmindckm.github.io/markmind-docs/#/basic)
-   [Display basic mode to outline](https://markmindckm.github.io/markmind-docs/#/outline)
-   [Display basic mode to table](https://markmindckm.github.io/markmind-docs/#/table)
-   [Create rich mode of mindmap](https://markmindckm.github.io/markmind-docs/#/rich)
-   [Get markdown text from rich mode of mindmap](https://markmindckm.github.io/markmind-docs/#/markdown)
-   [Copy and paste node of mindmap](https://markmindckm.github.io/markmind-docs/#/copy)
-   [Embed mindmap in other markdown file](https://markmindckm.github.io/markmind-docs/#/embed)
-   [Common operations of mindmap](https://markmindckm.github.io/markmind-docs/#/common)
    -   Drag image from desktop to rich mode of mindmap
    -   Copy text from browser to mindmap
    -   Drag multiple nodes

### PDF annotator

-   [Setup and features](https://markmindckm.github.io/markmind-docs/#/pdfAnnotator)
-   [Extracting annotations from pdf files](https://markmindckm.github.io/markmind-docs/#/highlight)
-   [Committing highlights and notes to pdf](https://markmindckm.github.io/markmind-docs/#/commitHighlight)
-   [Relate mindmap node with annotation](https://markmindckm.github.io/markmind-docs/#/relate)

---

## Introduction

Obsidian mark mind is a mind map,outline and pdf annotate tool base on obsidian api.

## Mind map introduction

it contains two modes : basic and rich

Add yaml to markdown:

```yaml
---

mindmap-plugin: basic (or rich)

---
```

Then you can find `Open as mindmap` menu in `more options`

## In `basic` mode

You can use the basic mind map function and use outline mode , it like the obsidian-enhancing-mindmap plugin.

### `basic` mode will output this markdown:

```
---

mindmap-plugin: basic

---

# Mark mind for obsidian

## Links
- <https://github.com/MarkMindLtd/obsidian-markmind>
- [GitHub](https://github.com/MarkMindLtd/obsidian-markmind)

## Related
- [coc-markmap](https://github.com/gera2ld/coc-markmap)
- [gatsby-remark-markmap](https://github.com/gera2ld/gatsby-remark-markmap)

## Features
- links
- **inline** ~~text~~ *styles*
- multiline
   text
- `inline code`
- Katex - $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
```

### Outline

You can add yaml to active outline mode:

```
---

mindmap-plugin: basic
display-mode: outline

---

```

#### Outline short cut

Features

Short Cut

New Brother Node

Enter

Indent

Tab

Unindent

Shift+Tab

Zoom in

Ctrl/Cmd+] Or Double Click Dott

Zoom out

Ctrl/Cmd+[

Move Up Or Down Node

Ctrl/Cmd + up/down

![outline](https://user-images.githubusercontent.com/18719494/138630597-fc2396d1-c818-43dc-83eb-fa638d8a0028.gif)

### table

You can add yaml to active table mode:

```
---

mindmap-plugin: basic
display-mode: table

---

```

![table](https://user-images.githubusercontent.com/18719494/150626028-8d8733d5-8cd2-4eaf-b369-73ebbbcc5244.gif)

## In `rich` mode

You can use all functions of mind map .

-   add summary
-   add boundary
-   add node relate link
-   add free node

### Rich mode will output this markdown:

```markdown
---

mindmap-plugin: rich

---

# md 

​``` json
{...}
​```

```

The mindmap data will store to `json`.

### mindmap short cut

New Mind Map

Ctrl/Cmd+P

New child node

Tab

New brother node

enter

Delete node

Delete/Backspace

edit node

Space/dblclick node

Undo

Ctrl/Cmd+Z

Redo

Ctrl/Cmd+Y

Quit edit node

Tab

Expand node

Ctrl/Cmd + /

Collapse node

Ctrl/Cmd + /

Move node to another node

Drag and drop node

Tab node

Up/down/left/right

Zoom in/out

Ctrl/Cmd + mouse wheel

Mind map to center

Ctrl/Cmd + E

Change mindmap layout

select node,Ctrl/Cmd + U / D / L / R / M / J / K / T / Q

delete summary / boundary / relate link

Delete/Backspace

---

![](https://user-images.githubusercontent.com/18719494/130028629-1a1e448d-32b9-4201-b152-1ad09439e18e.gif)

#### How to get markdown in `rich` mode ?

You can find `Copy as markdown` menu in `more options`.

![](https://user-images.githubusercontent.com/18719494/142220099-a69fa850-4ead-465a-98e5-f45611b48b55.gif)

#### How to export mindmap to image?

Use `ctrl + p` , execute `export to html` command

## PDF annotate

-   highlight text
-   area annotate
-   relate mind map node and annotate

### How to use pdf annotate

> You need download pdf js plugin ,Open setting tab to set up pdf plugin path , for example:D:plugins/pdfjs , It is a absolute path

[PC pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.4.5/pc.pdfjs.zip)  
[andriod pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.6/mobile.pdfjs.zip)  
[ios pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.6/mobile.pdfjs.zip)

#### Please ensure pdfjs folder have these folders

![folder](https://user-images.githubusercontent.com/18719494/163680014-432c40b6-899d-43dd-9547-48eb9577974f.gif)

#### How to set up your pdfjs plugin path?

-   download lastest pdfjs plugin ，unzip it
-   in andriod , create a `andriod` folder then put `pdfjs` folder in it
-   in ios , create a `ios` folder then put `pdfjs` folder in it
-   in pc , put `pdfjs` folder to `.obsidian` folder , in mac `command+shift+.` can show the hidden folder
-   ctrl/cmd + p , click `set up pdfjs plugin path`
-   restart obsidian and check path in obsidian markmind setting tab

![pdfjs](https://user-images.githubusercontent.com/18719494/167292216-78804074-5d72-4a29-b3ad-ecf14ae44fdf.gif)

The pdf js path need set separately and if it is not work above in ios , you can try `filza` app , it can find obsidian path

### Markdown

Add yaml to markdown file:

```
---

annotate-target: test/test.pdf
annotate-type: pdf

---
```

Then you can find menu `annotate pdf` in `more options`;

### About screenshot folder of rect annotations

1.  you can set up folder path ( this is a relative path , pointer to folder of your vault ) to save screenshot folder of rect annotations in setting tab
2.  or you can add folder path in yaml

```
---

annotate-target: test/test.pdf
annotate-type: pdf
annotate-image-target: assets/image

---
```

### short cut of pdf annoate

Features

Short Cut

Highlight Yellow

CTRL/CMD/ALT + Y

Highlight Green

CTRL/CMD/ALT + G

Highlight Blue

CTRL/CMD/ALT + B

Highlight Pink

CTRL/CMD/ALT + P

Highlight Red

CTRL/CMD/ALT + R

Delete annotate

CTRL/CMD/ALT + Delete/Backspace

### Mind Map and pdf annotate

1.  Open as mind map
2.  Use `[[]]` to reference pdf
3.  Click pdf reference , it will open a pdf reader if pdf plugin path is correct
4.  Use pdf annotate function
    -   it will create `annos` file in your folder as default, the `annos` file store annotations data,`annos` file is a `json` file in fact
    -   if you select (save pdf annotation type ) `markdown` in setting tab , it will create `${pdf name}-annotate.md` file in your folder. Each annotation has an associated quote block with a block reference. please do not modify these blocks

### How to relate mind map node and annotate?

There are three ways to relate mind map node and annotate

#### Default (only support rich mode)

-   make a pdf annotate
-   click pdf annotate
-   edit mind map node , `ctrl/cmd + v` to relate node and annotate
-   click node pdf annotate mark will auto copy `id` of annotate to clipboard

#### Support `obsidian://jump-to-pdf` protocol (support basic and rich mode)

-   open protocol support in setting tab
-   automatic create PDF annotation reference link and copy to clipboard when click pdf-annotate
-   paste to markdown file

#### If you use markdown to save pdf annotations (support basic and rich mode)

-   you can use `[[${md name}#${block reference}]]` to associate quote block with a block reference.
-   An obsidian link to an annotation block-reference will, when clicked, open the corresponding file and scroll to the associated highlight. If the file is already open in a pane, then the link will cause the existing pane to scroll instead.

### How to import pdf highlight annotations?

[see it](https://github.com/MarkMindCkm/obsidian-markmind/releases/tag/1.3.5)

### Demonstration

![](https://user-images.githubusercontent.com/18719494/130031749-84b84833-a52c-4ad1-b589-00eb2d8af317.gif)

## Donating

[![](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=markmind&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff)](https://www.buymeacoffee.com/markmind)

## Change log v1.5.2

1.  add layout for rich mindmap
2.  [obsidian markmind docs](https://markmindckm.github.io/markmind-docs)

---

![1234](https://user-images.githubusercontent.com/18719494/179392911-6f526b3f-3b57-475a-973d-38e1446377a5.gif)

### v1.5.0

1.  fix #356 , now support drag node to summary root in rich mode mindmap
2.  fix cannot delete node layout bug
3.  support batch delete nodes in rich mode ， use `delete/backspace` key to delete node

---

![delete nodes](https://user-images.githubusercontent.com/18719494/172137807-f0aefce2-1f29-443a-94af-2f95138b6224.gif)

![rich](https://user-images.githubusercontent.com/18719494/171544455-650cd9c5-0fe4-4177-8d29-618ae2b76df0.gif)

---

### v1.4.5

1.  Support auto add to selected node or root of mind map when annotate pdf in pc , please update for this feature [pc pdfjs](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.4.5/pc.pdfjs.zip)
2.  Support drag nodes to another node , fix #304
3.  fix #312

---

![test1](https://user-images.githubusercontent.com/18719494/166091478-4cd1883c-7adf-4b00-af70-7b85c26ae796.gif)

![test2](https://user-images.githubusercontent.com/18719494/166091482-ef936504-15a4-48ef-aca1-6c69028e23d8.gif)

### v1.4.4

1.  fix #280
2.  fix parse obsidian callout bug
3.  tip
    -   Set color group on the settings tab to define the color of the node line , the value is like : `red,orange,yellow,green,blue,#ccc,rgb(10,10,10)`
    -   Set node color group to define board color when click node

### v1.4.3

### mindmap

1.  fix #268 , fix bug of `fish` layout in `rich` mode
2.  node support parse callout of obsidian in `rich` mode

### pdf annotator

> please update [pc pdfjs](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.4.3/pc.pdfjs.zip)

the short cut change to this ( Mac can use this short cut)

Features

Short Cut

Highlight Yellow

CTRL/CMD/ALT + Y

Highlight Green

CTRL/CMD/ALT + G

Highlight Blue

CTRL/CMD/ALT + B

Highlight Pink

CTRL/CMD/ALT + P

Highlight Red

CTRL/CMD/ALT + R

Delete annotate

CTRL/CMD/ALT + Delete/Backspace

---

### Node support parse callout of obsidian in rich mode

![callout](https://user-images.githubusercontent.com/18719494/162611444-eb67ab20-01cf-4da1-b19f-126a1c2808b9.gif)

### v1.4.2

### PDF annotate tool

1.  support annotate `http(s)` , you should ensure obsidian can access to PDF file , for example

```
---
annotate-type: pdf
annotate-target: https://mozilla.github.io/pdf.js/legacy/web/compressed.tracemonkey-pldi-09.pdf
---

```

2.  fix #253 , when export highlight of pdf , only keep color value , you can setup export pdf format in setting tab to this , then it can be use with admonition

```
Page:{{page}}
<span style="color:rgb({{color}})">■</span>:{{highlightText}}
Comment:{{comment}}
[📌]({{link}})
^{{id}}
```

### mindmap feature

1.  support setup layout in yaml of `basic` mode , for example

```
---
mindmap-plugin: basic
mindmap-layout: fish
mindmap-layout-direct: right
---
```

notice :**  
keep setup value `mindmap-layout` and `mindmap-layout-direct` at the same time**

now support layout and direct  
|layout|direct|  
|---|---|  
| mindmap | right/left/mindmap|  
|fish| right/left|

2.  support create hand drawn mode from `basic` mode , and support export to image but not support edit mode in hand drawn mode , this is a testing feature and this feature will apply to `rich` mode in future

the default hand draw font is this in `style.css` , load font need network

```css
@font-face{
  font-family: 'myFont'; 
  src:url('http://cdn.ghost-jack.top/chinese.ttf');
}
.mm-handdraw-theme{
  font-family:'myFont';
}
```

you can change font to your own font in `style.css` , for example :  
(use `app://local/absolute font path` to load your local font , not need network)

```css

@font-face{
  font-family: 'testFont'; 
  src:url('app://local/D:font/test.ttf');
}
.mm-handdraw-theme{
  font-family:'testFont';
}

```

---

![handdraw1](https://user-images.githubusercontent.com/18719494/161531764-31ec36cf-e102-45f9-adf2-7c93240ab38c.gif)

![下载 (1)](https://user-images.githubusercontent.com/18719494/161531939-b3c997e3-54ed-4d70-98fa-b6e00307bc93.png)

---

### v1.4.1

1.  fix #237
2.  fix #236
3.  fix mindmap scale bug
4.  support add callout in `rich` mode ， support mobile and pc

---

![callout](https://user-images.githubusercontent.com/18719494/159688695-8d6fee36-29cb-4171-9b22-ae353a7e32fe.gif)

### v1.4.0

notice : v1.3.9 has update pdfjs plugin . [See detail](https://github.com/MarkMindCkm/obsidian-markmind/releases/tag/1.3.9)

1.  fix #231 ， you can add `link` variable in setting tab when export pdf annotations

```
Page:{{page}}
<span style="color:{{color}}">■</span>:{{highlightText}} 
Comment:{{comment}}
[📌]({{link}})
^{{id}}
```

2.  fix #174 , it can work directly with Obsidian Extended Table plugins [https://github.com/aidenlx/table-extended](https://github.com/aidenlx/table-extended) ， when use `table` mode , you can find a menu `get markdown of this table` , click it ,then copy it to a md file , open table-extended plugin ,notice : not support wrap in table

```
---
mindmap-plugin: basic
display-mode: table
---
```

3.  list mode support parse `![[mind map md]]` to a real mind map
4.  fix basic mode mind map parse `![[mind map md]]` bug

##### table mode with table extended plugin

![table](https://user-images.githubusercontent.com/18719494/158053432-d1956d65-a6e4-40fb-8003-0e757fe3b30d.gif)

##### export pdf annotations

![highlight](https://user-images.githubusercontent.com/18719494/158053715-7c72d63c-93c0-4a53-9d2e-0014fb2c8086.gif)

### v1.3.9

**notice** : pc pdfjs plugin need update [pc pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.9/pdfjs.zip)

### pdf js plugin

1.  add a short cut `ctrl + c` to select text
2.  fix cannot click `copy btn` bug when click a annotate
3.  fix loss `annotate-image-target` bug when save pdf annotations

```
---
annotate-type: pdf
annotate-target: pdf/test.pdf
annotate-image-target: test/test
---

```

### mind map

1.  add scale button in mind map
2.  fix #226 , you can add `color` variable in setting tab when export pdf annotations

```
Page:{{page}}
<span style="color:{{color}}">■</span>:{{highlightText}} 
Comment:{{comment}}
^{{id}}
```

![scale](https://user-images.githubusercontent.com/18719494/157392342-2372b4bd-8df9-4b84-9c18-6d1289cbea9b.gif)

![color1](https://user-images.githubusercontent.com/18719494/157392356-e1d97963-2665-43e7-b048-681d0a863429.gif)

1.  support search mindmap node ， add a menu `toggle search box` in `more options`
2.  fix #203 , support only copy pdf annotate text
3.  support micro adjustment of the height of the pdf annotate. you can add an upward or downward adjustment distance in the setting tab
4.  add a short cut `alt + i` to `toggle create rect annotate status`
5.  fix #131 , support set up folder path for image of rect annotate in yaml , this is a relative path to a folder in your vault , please update [pc pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.8/pdfjs.zip)

```
---
annotate-type: pdf
annotate-target: pdf/test.pdf
annotate-image-target: test/test
---
```

#### copy text

![copyText](https://user-images.githubusercontent.com/18719494/156492427-e7a046e6-4782-4312-a03b-1e3ec98262a2.gif)

#### add folder path for image of rect annotate

![imageFolder](https://user-images.githubusercontent.com/18719494/156492495-6ab436cb-4698-495c-9650-ee53622001c5.gif)

#### adjust height of annotate

![adjustHeight](https://user-images.githubusercontent.com/18719494/156492522-322cdeb5-6a41-48ed-84c4-9ac9455efcf0.gif)

#### search node

![search](https://user-images.githubusercontent.com/18719494/156496411-05d6afd8-6030-4878-819a-3cd07b479a22.gif)

### v1.3.7

1.  add command to toggle version of pc pdfjs plugin in command board （ctrl + p）
2.  please update PC pdfjs plugin [pc pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.7/pdfjs.zip)

-   support old and new version （ #197 ）
-   support highlight text by use shortcut key ( alt + y/r/g/p/b )
-   fix #197
    -   In rare cases, due to the problem of PDF format, there will be problems in the text selection of the new version. You can use the old version to solve them
    -   Generally, please use the new version ,better experience with the new version

3.  v1.3.6 has update mobile pdfjs plugin [https://github.com/MarkMindCkm/obsidian-markmind/releases/tag/1.3.6](https://github.com/MarkMindCkm/obsidian-markmind/releases/tag/1.3.6)

---

![pc pdfjs](https://user-images.githubusercontent.com/18719494/154829513-224a003d-5892-49b3-ba02-f39e72557ce6.gif)

### v1.3.6

1.  fix #196
2.  fix #184
3.  mobile pdfjs plugin is release , please download [mobile pdfjs](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.6/mobile.pdfjs.zip)

notice: long touch to select text

[https://user-images.githubusercontent.com/18719494/154784360-9a502fe8-843c-416f-8d56-b895bdad6399.mp4](https://user-images.githubusercontent.com/18719494/154784360-9a502fe8-843c-416f-8d56-b895bdad6399.mp4)

### 1.3.5

1.  fix #159
2.  support create rich mode from basic mode , you can use ctrl + p , then you can find `change basic to rich mode` command
3.  `import highlight annotations from pdf` this function is release , you can find a menu in 'more options' when open a pdf
4.  support export pdf annotations as a format , you can find a menu in `more options` , you can setup format in setting tab , the default format is

```
Page:{{page}}
Text:{{highlightText}} 
Comment:{{comment}}
^{{id}}
```

![123456](https://user-images.githubusercontent.com/18719494/153592129-842da678-cd8d-46fe-8df6-8c7238d0f583.gif)

![1234567](https://user-images.githubusercontent.com/18719494/153592138-c4899a71-cc4d-4f68-9707-fdddd4a228f3.gif)

![12345678](https://user-images.githubusercontent.com/18719494/153593116-5a725dfc-70f0-4a17-a9ad-3c2bccb70f99.gif)

### 1.3.4

1.  reconstruct PDF annotation , this is only for pc version [pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.4/pdfjs.zip)
2.  optimize some mind mapping functions

---

![pdf](https://user-images.githubusercontent.com/18719494/152282005-8f00b132-018d-4154-b4b9-0b4d334623a7.gif)

![pdftest](https://user-images.githubusercontent.com/18719494/152311838-05ffdbb4-3040-4a82-afd5-f0165bb016df.gif)

### v1.3.3

notice : v1.3.2 pc pdf js plugin has update , [pdfjs](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.2/internal-pdfjs.zip)

1.  support change relate link of node , now support line/polyline/bessel curve
2.  add a theme , support for white board

     `---  mindmap-plugin: rich mindmap-theme: whiteboard  ---`
     

![11](https://user-images.githubusercontent.com/18719494/150154942-6a62497b-2264-4435-9d05-4cd421455b76.gif)

![12](https://user-images.githubusercontent.com/18719494/150155333-5e3b06c6-5620-4121-9adb-c3f976774d84.gif)

![13](https://user-images.githubusercontent.com/18719494/150158918-3ac0b308-7745-4dbb-bab5-715ccc9d1c5c.gif)

### 1.3.2

### update

1.  fix parsemindmap mdin `table` mode
2.  fix parsetable mode mindmap mdto real table in node of mindmap/markdown file
3.  fix export table mode mindmap to html
4.  fix #157
5.  support create free node , the text is `![[ file name]]` when drag file of vault to `rich` mode,the extension support md/png/gif/jpg
6.  `get markdown table` added in `options` when in table mode

### Internal test function , allow only purchased users to use

please update pc pdfjs [download internal pdfjs](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.2/internal-pdfjs.zip) and manual download obsidian markmind [download internal ob markmind](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.3.2/internal-obsidian-markmind.zip)  
pc pdfjs support `import existing PDF highlights` (in more options) , #99

---

![11](https://user-images.githubusercontent.com/18719494/149620970-f3556f46-33bf-434f-b99e-3d6ff72bd2d6.gif)

![12](https://user-images.githubusercontent.com/18719494/149620976-2bc3702d-2f32-4f7f-a7a2-ee57d832fb8f.gif)

---

### Internal test function

![import](https://user-images.githubusercontent.com/18719494/149621321-45664041-e40f-4599-a25e-bdc39e977a28.gif)

### 1.3.1

Making table in markdown is very troublesome, so `table` mode is added to `basic` mode for make table visually

-   you can add `display-mode: table` in `basic` mode yaml
-   or you can find `open as table` in `more options`
-   support get table html code , you can find `get table html` in `more options` when in `table` mode
-   support `enter/tab` short cut , support edit text by dblclick
-   not support drag and drop , you can change node position in `mindmap` mode

mindmap-plugin: basic  
display-mode: table

---

![table](https://user-images.githubusercontent.com/18719494/148937281-3ff868b3-ccb6-404e-8f37-14b8e153feb5.gif)

![table1](https://user-images.githubusercontent.com/18719494/148937290-55fa7630-65d3-4b62-9e24-978f0de4c180.gif)

### 1.3.0

fix #152  
fix #150  
fix #149

### v1.2.9

1.  add a layout `vertical time` , the short cut is `ctrl + k`
2.  add a layout `fish right` , the short cut is `ctrl + q`
3.  add a layout `fish left`, the short cut is `ctrl + t`

Previous projects have been basically completed , this is plan for this year [https://github.com/MarkMindCkm/obsidian-markmind/projects](https://github.com/MarkMindCkm/obsidian-markmind/projects)

---

![fish1](https://user-images.githubusercontent.com/18719494/148394155-8fb4007e-6061-4ea3-8693-d27bbc036f33.gif)

### v1.2.8

fix parsemindmap md namebug when node has image  
fix style of node

### v1.2.7

1.  fix #138
2.  fix #130
3.  fix #129 , support parsemindmap md nameto mindmap in mindmap node
4.  fix #124 , support parsemindmap md nameto mindmap in md file

---

![test](https://user-images.githubusercontent.com/18719494/147801351-23842bd9-af20-4589-9459-774618bd5dac.gif)

![test1](https://user-images.githubusercontent.com/18719494/147801356-3edca7dc-d0ea-4213-9974-a37f71aa438c.gif)

![test2](https://user-images.githubusercontent.com/18719494/147801360-ed8aba1d-3dcf-4b97-a7a0-6dfc41597cd1.gif)

### v1.2.6

1.  add more options of canvas size in setting tab
2.  optimize the logic of the pop-up node setting box
3.  support export mindmap to html , use ctrl + p , then you can find export to html command , notice :
    -   not support blank link
    -   not suportsvg/pdf/mp4, only supportpng/jpgin node , image in mindmap must be local
    -   support export mathematical formul
    -   not support mobile
    -   If the mind map is too large, it cannot be exported , max export size is 16384 * 16384 (px)

---

![1234](https://user-images.githubusercontent.com/18719494/147195606-3a270e5e-2628-4322-bd87-9ef6d1004b66.gif)

### 1.2.5

-   Optimize the interaction of node setting box
-   ctrl/cmd + mouse click to select nodes , not support right click
-   add set up mac pdf js plugin path
-   notice : enhancing mindmap support export mindmap to image , it will be transplanted soon

### 1.2.4

-   Right click to select nodes and left click to move the mind map
-   In rich mode , support set up node background/stroke/text color/text size，if you want to change colors of node setup board , you can input setup board color in setting tab please restart obsidian

### 1.2.3

fix v1.2.2 tab/enter bug

### v1.2.2

1.  fix #108
2.  fix #103
3.  add `copy and paste` command (ctrl + p ) , support copy and paste node on mind maps
4.  Optimize input, select the node, press spacebar to edit the node in append mode, and press other keys to edit in overwrite mode

### v1.2.1

**Nitice:**  
Please update pdfjs plugin to v1.2.0 , the pc support epub file , the detail is there [v1.2.0](https://github.com/MarkMindCkm/obsidian-markmind/releases/tag/1.2.0)

fix set up pdf js plugin bug

**_How to set up pdf js plugin_**

-   download lastest pdfjs plugin ，unzip it
-   in andriod , create a `andriod` folder then put `pdfjs` folder in it
-   in ios , create a `ios` folder then put `pdfjs` folder in it
-   open a mind map
-   call up command board , then you can find a set up mobile pdfjs plugin path command , click it
-   restart obsidian and check path in obsidian markmind setting tab

The pdf js path need set separately and if it is not work above in ios , you can try `filza` app , it can find obsidian path

### v1.2.0

**Important**  
Please update pdfjs plugin , pc version support epub file , mobile will support near future  
[PC pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.2.0/pdfjs.zip)  
[andrios pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.2.0/andriod.pdfjs.zip)  
[ios pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.2.0/ios.pdfjs.zip)

---

1.  fix #87
2.  support read and annotate epub file,this is beta function

add yaml to md

---

annotate-target: test.epub
annotate-type: epub

---

then you can find `annotate epub` in `more options`

3.  fix miss `$` when save data bug
    
4.  simplify set up mobile pdfjs plugin path
    
    -   download lastest pdfjs plugin ，unzip it
    -   in andriod , create a `andriod` folder then put `pdfjs` folder in it
    -   in ios , create a `ios` folder then put `pdfjs` folder in it
    -   open a mind map
    -   call up command board , then you can find a `set up mobile pdfjs plugin path` command , click it

---

### epub

![test1](https://user-images.githubusercontent.com/18719494/144242980-afc1100c-c31e-4d80-9cc8-6eb46387ec6c.gif)

### set up mobile pdf js plugin path

[https://user-images.githubusercontent.com/18719494/144244497-4dd9e79c-3b50-4974-81c8-ea1a7ef92310.mp4](https://user-images.githubusercontent.com/18719494/144244497-4dd9e79c-3b50-4974-81c8-ea1a7ef92310.mp4)

### v1.1.9

**Important : ios pdfjs plugin update !**

1.  fix cannot use highlight text in ios system [download ios pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.9/ios.pdfjs.zip)
2.  support parse code block in markdown file , you should open it in setting tab and restart obsidian
    

```mindmap

# Mark mind for obsidian

## Links
- <https://github.com/MarkMindLtd/obsidian-markmind>
- [GitHub](https://github.com/MarkMindLtd/obsidian-markmind)

## Related
- [coc-markmap](https://github.com/gera2ld/coc-markmap)
- [gatsby-remark-markmap](https://github.com/gera2ld/gatsby-remark-markmap)

## Features
- links
- **inline** ~~text~~ *styles*
- multiline
   text
- `inline code`
- Katex - $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
  
```

---

![1234](https://user-images.githubusercontent.com/18719494/142712174-9ee6abc8-7aed-4159-940d-3dae6561e559.gif)

#### ipad annotate

[https://user-images.githubusercontent.com/18719494/142714629-29808aa0-4d5d-46c8-8bd4-037c28dc33ae.mp4](https://user-images.githubusercontent.com/18719494/142714629-29808aa0-4d5d-46c8-8bd4-037c28dc33ae.mp4)

### v1.1.8

**important**: please update pc pdf js to v1.1.7

[pc pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.7/pdfjs.zip)

1.  support a new layout in `rich` mode of mind map , the short cut is `Ctrl/Cmd + J`
2.  support import xmind zen file in `rich` mode of mind map , the way is drag xmind zen file and drop to blank space of mind map in `rich` mode
3.  fix some times can not add/remove free node bug

This is a xmind zen [demo](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.8/note.taking.1.xmind)

---

Import xmind zen file  
![note 12367133](https://user-images.githubusercontent.com/18719494/141953779-f7e1fdf2-8e0f-4ab0-b099-7d5bfb7a07f5.gif)

`Ctrl + J` change to new layout  
![note 12367133tt](https://user-images.githubusercontent.com/18719494/141953811-9657cf8d-e04e-4c7b-8499-154f9e3272d5.gif)

### v1.1.7

**important**: please update pc pdf js

[pc pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.7/pdfjs.zip)

1.  fix `basic` mode can add free node bug
2.  fix export annotate pdf in pc version

### v1.1.6

**important**

> please update pc pdfjs plugin ， mobile pdfjs plugin will update next version

[PC pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.6/pdfjs.zip)

1.  fix #60 , add pdf annotate short cut
2.  fix #61
3.  fix #64
4.  fix #66
5.  mindmap node support smooth move , you shoud open it in setting tab
6.  In rich mode of mindmap , double click the blank space can add free node
7.  fix #57

pdf annotate Features

Short Cut

Highlight Yellow

ALT + Y

Highlight Green

ALT + G

Highlight Blue

ALT + B

Highlight Pink

ALT + P

Highlight Red

ALT + R

Delete annotate

ALT + Delete/Backspace

![note 1236](https://user-images.githubusercontent.com/18719494/140644085-fc8c9f2e-d058-4ff5-a436-7edd58e33b42.gif)

### v1.1.5

**important:**  
Please update pdfjs plugin to v1.1.1 version

PC : [PC pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.6/pdfjs.zip)  
Andriod [Andriod pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.0/mobile.pdfjs.zip)  
iPhone/iPad : [iPhone/iPad pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.9/ios.pdfjs.zip)

1.  support add note to mind map node in rich mode , note support markdown
2.  summary node support add child node
3.  (ctrl + p) add a command `get base path of vault` , it will auto copy to clipboard

---

![note](https://user-images.githubusercontent.com/18719494/139576838-812bf0c5-84e5-452e-accb-738517ebe7a9.gif)

![123421](https://user-images.githubusercontent.com/18719494/139576842-3a2293a5-8238-4eb6-8475-1071ee5f14f5.gif)

### v1.1.4

fix delete summary bug when edit node use backspace/delete key

### v1.1.3

fix #54  
fix #28  
fix miss code and link bug in outline mode

### v1.1.2

fix #46  
add `set mindmap to center` menu in `more options`

### v1.1.1

**important:**  
Mobile pdf js plugin need to download again

PC: [PC pdfjs plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.6/pdfjs.zip)  
Andriod [Andriod pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.0/mobile.pdfjs.zip)  
iPhone/iPad : [iPhone/iPad pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.1/ios.pdfjs.zip)

1.  fix iPhone/iPad cannot use pdf annotate bug

Please set up pdfjs path in setting tab , this is a absolute path ,( you can find absolute path of your vault in obsidian app ) the best way is create a folder in your vault , for example :`plugin` folder, then put pdfjs plugin in it

**About iPhone/iPad pdfjs path**:  
for example (iPad), you create `plugin` folder in your vault , then put `pdfjs plugin` into it , the path will like this  
`/var/mobile/Containers/Data/Application/FACF6387-DAA2-45B3-8F52-3536E1EC29A1/Documents/plugin/pdfjs`

`FACF6387-DAA2-45B3-8F52-3536E1EC29A1` are different on each device

**About andriod pdfjs path**,like this  
`/storage/emulated/0/Documents/obsidian/obsidian/plugin/pdfjs`

**About PC pdfjs path**,like this

`D:plugin/pdfjs`

---

iPad screen short  
![68747470733a2f2f692e6c6f6c692e6e65742f323032312f31302f31312f3431557933536d756a4b723835515a2e706e67](https://user-images.githubusercontent.com/18719494/136878933-3c86d930-e2fd-4dd4-8c1e-8c4de6cc1ac7.png)

### v1.1.0

**Important**  
In this version ,You should download pdfjs plugin again

PC : [Pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.7/pdfjs.zip)  
Andriod [Andriod pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.0/mobile.pdfjs.zip)  
iPhone/iPad : [iPhone/iPad pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.1/ios.pdfjs.zip)

You should set up pdf js plugin path in setting tab , it is a absolute path  
**For example** :

-   `D:plugins/pdfjs` in pc
-   `/storage/emulated/0/Documents/obsidian/obsidian/plugin/pdfjs` in andriod

you should put pdfjs plugin to a accessible folder in mobile .  
you can find your vault path in mobile app , the best way is create a folder(for example `plugin` folder) in your vault , then put pdfjs plugin in it.

1.  fix #40 ， you can select mode of mindmap (when create mindmap) in setting tab , the default is `basic`
2.  pdf annotate support mobile , only support pdf of your vault , not support `file://`
3.  in md file , support use `[[md#^node id]]` to reference node of `rich` mode mindmap , you can find menu `copy node id` in `more options`
4.  support set up image folder in setting tab to save image of pdf rect annotate .
    -   for example : `Screenshot` , the Screenshot folder must be exists in your vault, the image of rect annotate will be save to `Screenshot` folder
5.  fix when annotate `file:// pdf path` cannot use rect annotate bug
6.  support 3 theme of mindmap , you can add yaml to markdown

```
---

mindmap-plugin: basic( or rich )
mindmap-theme: dark(or light or card)  

---
```

Markmind all functions will support mobile and pc from this version ,andriod/apple/window/linux has consistent experience.

![](https://user-images.githubusercontent.com/18719494/136696974-a776ad2c-aab5-4d62-917f-2b294d1da40a.gif) ![](https://user-images.githubusercontent.com/18719494/136696996-36cd0e77-8212-4b6f-8f55-6dbf617cf906.gif)

![动画1211713467](https://user-images.githubusercontent.com/18719494/136694951-9bb9720d-b5e3-4622-8929-70de6fb7f24a.gif)

## v1.0.9

### this is a big version

1.  fix #4 , pdf annotate support all pdf files on disks by using `file://` ，this feature can only use to desktop app , if you use `file://` , the annotatios will be save to this markdown file

```
annotate-target: file://pdf absolute path
annotate-type: pdf

```

2.  fix #29 , support mobile from this version， it has consistent experience with desktop version
    
3.  add command :
    

-   select node , change layout in `rich` mode of mindmap
-   toggle markdown and mindmap mode
-   add some menus of `more options` in `rich` mode of mindmap ，(copy text to clipboard automatic)
    -   Copy node text as markdown (contains children)，the text type like `basic` mode
    -   Copy node text (only this node)
    -   Copy node links , you can reference it in other md file

4.  support change summary/boundary/relate link color
5.  if you set up active code in setting tab of desktop version , it will create mobile active code in your plugin obsidian-markmind data.json automatic
6.  support move root of mindmap in rich mode

![12117](https://user-images.githubusercontent.com/18719494/135819440-34380383-0a3a-481c-b5ac-205f6a9da155.gif)  
![](https://user-images.githubusercontent.com/18719494/135823093-f34d6870-7dfb-4646-8874-1347ad5047f0.gif)

### v1.0.8

fix #26  
fix miss markdown format in `list` mode when use ctrl + down / up

### v1.0.7

fix #24 , fix pdf select multi line to highlight , this problem is caused by pdf plugin

**Important**:  
**You should to download the pdfjs plugin again PDFJS Plugin, it keep more functions and it support multi open**  
PC : [Pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.7/pdfjs.zip)  
Andriod [Andriod pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.0/mobile.pdfjs.zip)  
iPhone/iPad : [iPhone/iPad pdf js plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.1.1/ios.pdfjs.zip)

### v1.0.6

emergency fix #22  
emergency fix #21

### v1.0.5

emergency fix mindmap `rich` mode bug

### v1.0.4

This is a big version:  
**Notice**:  
**You should to download the pdfjs plugin [PDFJS Plugin](https://github.com/MarkMindCkm/obsidian-markmind/releases/download/1.0.7/pdfjs.zip), it keep more functions and it support multi open**

1, fix #18 , you can select pdf viewer theme in setting tab  
2. fix #17  
3. fix #15  
4. fix #8  
5. Support multi open pdf annotate  
6. support add comment to annotation  
7. support committing highlights and notes to PDFs ，you can find `export pdf annotate` menu in more menus , it will create a file in your folder,the name is `${pdf name}-annotate.pdf`  
8. Split PDF annotation and mindmap function  
9. change in `basic` mode , mind map layout from `tree` to `mind map`  
10. fix #2 , in `rich` mode

-   if save data first time , it will output this markdown
-   if it is not the first time to save data , it will only replace '${mindmap data}', so you can change `md` file
-   if you want to reference node , it will automatic create mind map node reference link and copy to clipboard when click node and press ctrl or command
    

---

## mindmap-plugin: rich

# title

```json
  ${mindmap data}
```

---

The use type of PDF annotation has changed , if you want to use annotate function, you can add `yaml` to markdown file:

```
---

annotate-target: test/test.pdf
annotate-type: pdf

---
```

then you can find `annotate pdf` menu in more menus

1.  you can select `md` or `annos` to save annotations in setting tab

-   `annos` is default , it is `json` file in fact , you can use `obsidian://jump-to-pdf` to reference annotate ,
    -   annotations do not contaminate MD files When referenced
-   `md` is the recommended way
    -   you can use `obsidian://jump-to-pdf` to reference annotate
    -   or you canmd > ^block idto to reference annotate

2.  please open `obsidian://jump-to-pdf` protocol in setting tab