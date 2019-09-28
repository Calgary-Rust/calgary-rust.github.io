# Resources


## Installing the toolchain

[https://rustup.rs/](https://rustup.rs/)

You should consider installing the Rust linter Clippy, and depending on your editor capabilities, RustFormat:

    rustup component add clippy-preview
    rustup component add rustfmt-preview


## Offline books and docs

The Rust books, the full docs standard library as well as a few more reousrces are installed as part of the toolcahin. Once installed, run:

* `rustup docs` - opens a browser with links to locally installed docs, books etc...
* `rustup docs --path` - shows the path to the doccs on your local disk - useful in case you cannot open a browser from your session (eg: running rustup in WSL)
* `rustup docs -h` - display options and which books are available (`--std`, `--book`, `--cargo`, `--reference`, etc…
* `rustup docs --std` includes Rust built-in keywords, macros and primitive and the Standard library API documentation.

**Note**: All offline pages have a search function which works offline. Look for the search box or the 🔍 at the top of the pages.


## Online docs

* [The Rust book](https://doc.rust-lang.org/book/)

* [Rust documentation](https://doc.rust-lang.org/)

* [Rust by Example](https://doc.rust-lang.org/rust-by-example/)

* [Learning Rust](https://learning-rust.github.io/)


## Other resources to learn

* [Rust Bridge brief intro to Rust](https://intro.rustbridge.com/en/intro/#1): This is a very good first few step hands on intro to the Rust programming language.

* [Rustlings](https://github.com/rust-lang/rustlings): Once installed locally, it takes you through exercises, giving you code with bugs that you need to fix so they compile

* (exercism.io): Site with exercises to learn different programming languages. This can be slow as you need a mentor to review your code, but useful if you need somebody to help and give you feedback.


## Discord servers

Lots of channels based on topics, including "beginners":

* [Official Mozilla discord server](https://discordapp.com/invite/rust-lang)

* [Community Rust language discord server](https://discord.gg/aVESxV8)

## Are we yet?
There are a few "areweXXXyet.org" sites which try to capture current most popular solutions available for a given problem.
They are a good starting point if you want to explore a particular subject with Rust.
They are also typically hosted on github and accepting Pull Requests.

There is a Mozilla wiki page which maintains a list of areweyet sites: [https://wiki.mozilla.org/Areweyet](https://wiki.mozilla.org/Areweyet)

