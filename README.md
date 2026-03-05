# Awesome OCaml [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of awesome frameworks, libraries, tools, and resources for the OCaml programming language.

## Contents

- [Libraries](#libraries)
  - [Core Libraries](#core-libraries)
  - [Data Structures and Algorithms](#data-structures-and-algorithms)
  - [Web Frameworks](#web-frameworks)
  - [Testing](#testing)
  - [Concurrency and Parallelism](#concurrency-and-parallelism)
  - [Graphics and Visualization](#graphics-and-visualization)
- [Tools](#tools)
- [Build Tools and Package Managers](#build-tools-and-package-managers)
- [IDEs and Editors](#ides-and-editors)
- [Learning Resources](#learning-resources)
- [Books](#books)
- [Community](#community)
- [Contribute](#contribute)
- [License](#license)

## Libraries

### Core Libraries

- [OCaml Standard Library](https://ocaml.org/manual/stdlib.html) - The official standard library of OCaml.
- [Base](https://github.com/janestreet/base) - A Jane Street alternative to the OCaml standard library with additional features and improvements.
- [Core](https://github.com/janestreet/core) - An industrial-strength alternative standard library by Jane Street.
- [Containers](https://github.com/c-cube/ocaml-containers) - A lightweight extension of the OCaml standard library.

### Data Structures and Algorithms

- [Batteries](https://github.com/ocaml-batteries-team/batteries-included) - An alternative standard library providing additional data structures and utilities.
- [OCamlgraph](https://github.com/backtracking/ocamlgraph) - A library for graph data structures and algorithms in OCaml.
- [Seq](https://github.com/c-cube/seq) - A library providing a sequence data type with various utilities.

### Web Frameworks

- [Opium](https://github.com/rgrinberg/opium) - A lightweight and modular web framework for OCaml, inspired by Express.js.
- [Ocsigen Eliom](https://ocsigen.org/eliom/) - A powerful framework for full-stack web applications in OCaml.
- [Dream](https://aantron.github.io/dream/) - A modern, type-safe web framework for building reliable web applications in OCaml.
- [Cohttp](https://github.com/mirage/ocaml-cohttp) - A lightweight HTTP server and client library for OCaml.

### Testing

- [Alcotest](https://github.com/mirage/alcotest) - A lightweight and colorful test framework for OCaml.
- [OUnit](https://github.com/gildor478/ounit) - A unit testing framework for OCaml, similar to JUnit.
- [QCheck](https://github.com/c-cube/qcheck) - A property-based testing library inspired by Haskell's QuickCheck.

### Concurrency and Parallelism

- [Async](https://opensource.janestreet.com/async/) - A library for asynchronous programming, designed by Jane Street.
- [Lwt](https://ocsigen.org/lwt/) - A cooperative threading library for OCaml, providing lightweight threads.
- [Domainslib](https://github.com/ocaml-multicore/domainslib) - A parallel programming library for OCaml's multicore runtime.

### Graphics and Visualization

- [Graphics](https://ocaml.org/manual/4.11/libgraph.html) - The OCaml Graphics library for basic graphics operations.
- [Vg](https://erratique.ch/software/vg) - A declarative 2D vector graphics library for OCaml.
- [Plotkic](https://github.com/plotkic/plotkic) - A simple and lightweight plotting library for OCaml.

## Tools

- [OCamlFormat](https://github.com/ocaml-ppx/ocamlformat) - A tool for automatically formatting OCaml code.
- [Merlin](https://github.com/ocaml/merlin) - An editor helper that provides autocompletion and type-checking for OCaml.
- [utop](https://github.com/ocaml-community/utop) - An enhanced interactive toplevel (REPL) for OCaml with autocompletion.
- [dune](https://dune.build/) - A popular build system for OCaml projects, focused on simplicity and speed.

## Build Tools and Package Managers

- [OPAM](https://opam.ocaml.org/) - The OCaml Package Manager, a tool for managing OCaml libraries and dependencies.
- [Dune](https://dune.build/) - A build system for OCaml, designed for reliability and speed.
- [esy](https://esy.sh/) - A package manager for native projects, including OCaml.

## IDEs and Editors

- [VS Code](https://code.visualstudio.com/) - Supports OCaml via the [OCaml Platform extension](https://marketplace.visualstudio.com/items?itemName=ocamllabs.ocaml-platform).
- [Vim](https://www.vim.org/) - Configure with [ocaml-lsp](https://github.com/ocaml/ocaml-lsp) and [Merlin](https://github.com/ocaml/merlin) for a powerful OCaml development environment.
- [Emacs with Tuareg Mode](https://github.com/ocaml/tuareg) - An OCaml major mode for Emacs, supporting OCaml syntax highlighting and integration with Merlin.
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) - Supports OCaml via the [OCaml Plugin](https://github.com/JetBrains/intellij-ocaml).

## Learning Resources

- [Real World OCaml](https://dev.realworldocaml.org/) - A comprehensive and practical guide to OCaml programming.
- [OCaml.org Learning Resources](https://ocaml.org/learn/) - Official tutorials and guides for learning OCaml.
- [CS3110: Data Structures and Functional Programming](https://www.cs.cornell.edu/courses/cs3110/2024fa/) - A Cornell University course on OCaml programming.
- [OCaml MOOC](https://www.fun-mooc.fr/en/courses/ocaml-foundations-of-functional-programming/) - A free online course on functional programming with OCaml.

## Books

- *Real World OCaml* by Yaron Minsky, Anil Madhavapeddy, and Jason Hickey - A practical book on OCaml programming.
- *OCaml from the Very Beginning* by John Whitington - An introduction to OCaml for beginners.
- *Functional Programming in OCaml* by Michael R. Clarkson - A book focused on functional programming techniques in OCaml.
- *Unix System Programming with OCaml* by Xavier Leroy - A book on system programming using OCaml.

## Community

- [OCaml Discuss](https://discuss.ocaml.org/) - The official forum for OCaml discussions.
- [Reddit: r/ocaml](https://www.reddit.com/r/ocaml/) - A subreddit for OCaml-related news, questions, and discussions.
- [OCaml Discord](https://discord.gg/ocaml) - A chat server for the OCaml community.
- [Stack Overflow: OCaml](https://stackoverflow.com/questions/tagged/ocaml) - A Q&A site for OCaml programming questions.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
