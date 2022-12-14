# Markdown Processor

**The gist:** Build a library and command-line tool that takes a Markdown file, converts it to HTML, and outputs it to stdout.

There will definitely be libraries out there that already do this for a given language, usually many of them. But the fun here is in taking a pretty manageable specification like [CommonMark](https://commonmark.org/) and writing your own parser and translator to HTML.

## Spec

Let's call the program and lib `marcus`.

Command line:

```
marcus foo.md > foo.html
```

It'd be great if you could send it via pipes too, like `cat foo.md | marcus > foo.html`

If you're building the CLI out, it'd also be nice to have a library that you can use in that language as well.

```
Marus.to_html("# Hi\n[my link](/bye)\n")
```

Would output:

``` html
<h1>Hi</h1>

<p><a href="/bye">my link</a></p>
```

## Concepts

- Parsing text into a data structure and converting it into HTML
- Pipes and CLI if you go that route

## Stretch Goals

- Support converting HTML to MD
- Support bulk converting multiple files
- Add the ability to wrap the generated page in a template of HTML

## See Also

- [Custom Markup Language](./custom-markup-language.md)
