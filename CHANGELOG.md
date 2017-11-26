## 0.7.0
* Rename grammar selector: source.haxe -> source.hx
* Update to haxe 4
* Misc snippet fixes

## 0.6.0
* Snippets: cast, dynamic, using
* Snippets: std library top level definitions
* Grammars: recognises interpreter directives, emacs modelines, vim modelines

## 0.5.4
* Update grammar to haxe 3.4.0-rc.1

## 0.5.3
* Snippets: remove unnecessary line endings
* Snippets: description urls for Array/List/Map
* Snippets: remove Array/List/Map parentheses

## 0.5.2
* Fix scope name
* Snippets: null
* Snippets: hxml -D <v> definitions
* Spec: fixes "tokenizes the #{keyword} keyword"

## 0.5.1
*	Grammars cleanup
* Remove std lib grammars
* More snippet descriptions
* Add snippet for true/false
* Spec: add all keywords

## 0.5.0
* Fixed hxml grammar comment definition
* Added descriptions and urls to snippets
* Snippet for haxelib.json
* Spec tests
* TravisCI integration

## 0.4.5
* Grammar: remove flash specific std grammar definitions
* Fix hxml snippet
* Add missing hxml -version snippet

## 0.4.4
* haxe 3.3 support

## 0.4.3
* Snippets: minor `try/catch` improvement

## 0.4.2
* Syntax: `$type` is a keyword, not `type`

## 0.4.1
* Snippets: extra newline after 'package'
* Snippets: Snippets: List<T>, Map<K,V>

## 0.4.0
* Removed hss and swfml grammar
* Renamed grammar files to *-grammars.cson
* Split snippets for hx|hxml files into seperate files
* Required atom version >=1.5
* Snippets: suggest same placeholder as haxe prints with --help (<file>,[optional])
* Snippets: Allow to exit current at next line
* Snippets: -D key=value support
* Snippets: improved --wait

## 0.3.1
* Hxml: --each grammer

## 0.3.0
* Updated settings/language-haxe.cson path for compatibility with atom api 1.0

## 0.2.0
* Merged in grammars and some snippets from https://github.com/nicetrysean/atom-haxe
* Added my own snippets for .source.hx
* Added gif screenshots of snippets to README

## 0.1.0
* Conversion from Sublime Text package (which is from TextMate package)
