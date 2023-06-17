# codemirror-lang-gleam

This package implements basic Gleam language support for the
[CodeMirror](https://codemirror.net/6/) code editor.

## Language Support + Lezer Grammar

This includes both the CodeMirror `LanguageSupport` and the `LRLanguage` grammar all bundled into a single small repository with a simple build process.

## Maintainers

There is a very rough developer tool in `devtool` that can be used for testing.

```shell
npm run build-devtool
```

## API Reference

<dl>
<dt id="user-content-wren">
  <code>gleam() → <a href="https://codemirror.net/6/docs/ref#language.LanguageSupport">LanguageSupport</a></code></dt>

<dd><p>Wren support. Includes snippet completion.</p>
</dd>

<dt id="user-content-wrenlanguage">
  <code>gleamLanguage: <a href="https://codemirror.net/6/docs/ref#language.LRLanguage">LRLanguage</a></code></dt>

<dd><p>A language provider based on the Lezer Gleam
parser provided in this very same package.</p>
</dd>

<dt>
  <code>lezerParser: <a href="https://lezer.codemirror.net/docs/ref/#lezer.Parser">Lezer#Parser</a></code></dt>

<dd><p>Lezer Gleam parser.</p>
</dd>
