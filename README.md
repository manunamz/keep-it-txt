# keep-it-txt [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tip 25 - Keep Knowledge In Plain Text
> 
> ~<a target="_blank" href="https://www.amazon.com/gp/product/0135957052/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0135957052&linkCode=as2&tag=short2things-20&linkId=bdde2090bcfb3998e38a000d2e2cfc7a">The Pragmatic Programmer: Your Journey To Mastery, 20th Anniversary Edition (2nd Edition)</a>

The Three Laws influenced by ["CriticMarkup-toolkit"](https://github.com/CriticMarkup/CriticMarkup-toolkit#the-three-laws):

```
           ^
          / \
    human readability
        /     \	
  markdown compatibility
      /         \
   machine readability
     -------------
```

(importance rises upward, with each level dependent on the ones below it as a precondition.)

1. Markup shall be human readable. A human with a simple text editor can easily read and comprehend any text containing Markup.
2. Markup shall be compatible with existing markup syntax for Markdown and other Markup extensions.
3. Markup shall be computer readable.


- [markdown](https://github.com/mundimark/awesome-markdown)
  - [commonmark](https://spec.commonmark.org/)
  - [github flavored markdown](https://github.github.com/gfm/)
  - [latex](https://www.latex-project.org/)
  	- https://github.com/latex3/
  - [katex](https://katex.org/)
  	- https://github.com/KaTeX/KaTeX
  - [mermaid.js](https://github.com/mermaid-js/mermaid)
  - slides (see `bespoke` below)
  	- ex: [fusuma](https://github.com/hiroppy/fusuma)
  - [CriticMarkup](https://github.com/CriticMarkup/CriticMarkup-toolkit/)
  	- [CriticMarkup toolkit](https://github.com/CriticMarkup/CriticMarkup-toolkit)
  - [markvis](https://github.com/geekplux/markvis)
  - [dataview](https://github.com/blacksmithgu/obsidian-dataview) (a query language)
  	- [aspen](https://github.com/thepeergroup/aspen)
  - [chessboard.js](https://github.com/oakmac/chessboardjs/)
  	- [chess.js](https://github.com/jhlywa/chess.js)
  - [argdown](https://argdown.org/)
  - [abc.js](https://github.com/paulrosen/abcjs)
	- [vextab](https://vexflow.com/vextab/)
		- https://github.com/0xfe/vextab
  - [fountain](https://fountain.io/)
  	- https://github.com/piersdeseilligny/betterfountain
  	- https://github.com/nyousefi/Fountain
  - [maid](https://github.com/egoist/maid)
  - [mkcli](https://github.com/mkdoc/mkcli)
- [markdown-it](https://github.com/markdown-it/markdown-it)
	- [markdown-it-toc](https://github.com/jonschlinkert/markdown-toc)
	- [markdown-it-footnote](https://github.com/markdown-it/markdown-it-footnote)
	- ...
	- [markdown-it-music](https://github.com/music-markdown/markdown-it-music)
	- [markdown-it-argdown](https://github.com/christianvoigt/argdown/tree/master/packages/argdown-markdown-it-plugin)

- [markdownlint](https://github.com/DavidAnson/markdownlint)

- conversion
	- [pandoc](https://github.com/jgm/pandoc)
		- [pandif](https://github.com/davidar/pandiff)
	- [word-to-markdown](https://github.com/benbalter/word-to-markdown)

- data serialization
 	- [archieml](http://archieml.org/)
	- [CSV](https://www.loc.gov/preservation/digital/formats/fdd/fdd000323.shtml)
	  - TSV
	- [JSON](https://www.json.org/json-en.html)
	- [TOML](https://toml.io/en/)
	- [YAML](https://yaml.org/spec/)

- protocols ([rfc](https://www.rfc-editor.org/rfc/rfc-index.txt))
	- [HTTP](https://www.rfc-editor.org/rfc/rfc9110)
	- [SMTP](https://www.rfc-editor.org/rfc/rfc5321)
	- [IMAP](https://www.rfc-editor.org/rfc/rfc3501)

- further...
	- explorable explanations
		- [Idyll](https://github.com/idyll-lang/idyll)
	- finance
		- [plain text accounting](https://plaintextaccounting.org/)
	- presentation
		- (bespoke)[https://github.com/bespokejs/bespoke]
			- w/ [markdown-it](https://github.com/fegemo/bespoke-markdownit)
	- productivity
		- [org-mode](https://orgmode.org/)
		- [tiddlywiki](https://tiddlywiki.com/)


- other lists
	- [awesome-markdown](https://github.com/mundimark/awesome-markdown)
	- [awesome-markup](https://github.com/croqaz/awesome-markup)

---

- markdown parsers
	- c
		- [cmark-gfm](https://github.com/github/cmark-gfm)
	- js
		- [markdown-it](https://github.com/markdown-it/markdown-it)
		- [marked](https://github.com/markedjs/marked)
		- [remark](https://github.com/remarkjs/remark)
		- [remarkable](https://github.com/jonschlinkert/remarkable)
	- ruby
		- [kramdown](https://github.com/gettalong/kramdown)
	- rust
		- [comrak](https://github.com/kivikakk/comrak)
		- [pulldown-cmark](https://github.com/raphlinus/pulldown-cmark)

- ssg
	- blog
		- [11ty](https://www.11ty.dev/)
		- [astro](https://astro.build/)
		- [hugo](https://gohugo.io/)
		- [jekyll](https://jekyllrb.com/)
		- [middleman](https://github.com/middleman/middleman)
	- doc
		- [docusaurus](https://docusaurus.io/)
		- [slate](https://github.com/slatedocs/slate)

- other notable markup languages:
	- [textile](https://textile-lang.com/)
