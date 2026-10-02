# .Gram

**A source generator that compiles grammars into strongly typed C# parsers** — from single-character rules to the SQL standard.

The grammar is known at compile time, so the generated parser is ordinary C# in your own assembly: no parser engine, no grammar graph, no runtime library to interpret it.

- **Parse, TryParse and Find** APIs with typed results from named captures
- **Versions of one language** (dialects) from a single grammar
- **Streaming** parsers over `TextReader`, error recovery for record-oriented input
- **Compile-time diagnostics** that point back into the grammar
- **Visual Studio** support for `.gram` files and for grammars written inside a `[Gram]` string

### Packages

| Package | |
| --- | --- |
| [DotGram](https://www.nuget.org/packages/DotGram) | the generator |
| [DotGram.Sql](https://www.nuget.org/packages/DotGram.Sql) | T-SQL, SQL:2023 and SQL-92 parsers, script reader |
| [DotGram.Web](https://www.nuget.org/packages/DotGram.Web) | URIs, JSON, HTTP headers, cookies, e-mail addresses, language tags and more |
| [DotGram.Finance](https://www.nuget.org/packages/DotGram.Finance) | FIX protocol messages |
| [DotGram.ExpressionLanguage](https://www.nuget.org/packages/DotGram.ExpressionLanguage) | a C#-like expression language compiled to expression trees |

### Start here

- [README and getting started](https://github.com/dotgram/dotgram#getting-started)
- [Grammar notation](https://github.com/dotgram/dotgram/blob/main/docs/syntax.md) · [Diagnostics](https://github.com/dotgram/dotgram/blob/main/docs/diagnostics.md) · [Visual Studio](https://github.com/dotgram/dotgram#visual-studio)
- [Issues](https://github.com/dotgram/dotgram/issues)

MIT licensed · .NET Standard 2.0 · no runtime dependencies
