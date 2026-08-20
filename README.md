# Awesome Gleam with stars

For a full list of packages check out [**the Gleam package index**](https://packages.gleam.run/).

Have a Gleam project to share with the world? Add a file in `packages/` and run
`gleam run`.

Looking for something to build? Check out [the suggestions list][suggestions].

[suggestions]: https://github.com/gleam-lang/awesome-gleam/issues/34

* [Packages](#packages)
  * [API Clients](#api-clients)
  * [Benchmarking](#benchmarking)
  * [Build Tooling](#build-tooling)
  * [Command Line](#command-line)
  * [Configuration](#configuration)
  * [Cryptography](#cryptography)
  * [Data Structures](#data-structures)
  * [Databases](#databases)
  * [Email](#email)
  * [Erlang and OTP](#erlang-and-otp)
  * [Error Handling](#error-handling)
  * [File System](#file-system)
  * [Formats](#formats)
  * [Frontend](#frontend)
  * [Gleam](#gleam)
  * [Graphics](#graphics)
  * [HTML](#html)
  * [HTTP](#http)
  * [HTTP Clients](#http-clients)
  * [HTTP Servers](#http-servers)
  * [JSON](#json)
  * [JavaScript](#javascript)
  * [Logging and Monitoring](#logging-and-monitoring)
  * [Machine Learning](#machine-learning)
  * [Networking](#networking)
  * [Numbers](#numbers)
  * [Parsing](#parsing)
  * [Project Tooling](#project-tooling)
  * [Push Notifications](#push-notifications)
  * [Queues and Job Processing](#queues-and-job-processing)
  * [Randomness](#randomness)
  * [SDKs](#sdks)
  * [Standards](#standards)
  * [TUI](#tui)
  * [Templating](#templating)
  * [Testing](#testing)
  * [Text](#text)
  * [Time](#time)
  * [Validation](#validation)
  * [Web frameworks](#web-frameworks)
  * [Websites](#websites)
* [Projects](#projects)
  * [Compilers](#compilers)
  * [Web applications](#web-applications)
  * [Network applications](#network-applications)
* [Tools](#tools)
  * [Editor support](#editor-support)
* [Resources](#resources)
  * [Websites](#websites)
  * [Courses](#courses)
  * [Social Media](#social-media)

## Packages

### API Clients

* [telega](https://github.com/bondiano/telega-gleam) ⭐ 67 | 🐛 0 | 🌐 Gleam | 📅 2026-07-23 - [📚](https://hexdocs.pm/telega/) - A Gleam library for the Telegram Bot API with HTTP-based APIs, client implementation, wisp adapter, session bot, and conversation support
* [discord\_gleam](https://github.com/Cyteon/discord_gleam) ⭐ 52 | 🐛 1 | 🌐 Gleam | 📅 2026-07-05 - [📚](https://hexdocs.pm/discord_gleam/) - A library to create discord bots in gleam
* [glevatar](https://github.com/bunopnu/glevatar) ⭐ 8 | 🐛 0 | 🌐 Gleam | 📅 2024-04-13 - [📚](https://hexdocs.pm/glevatar/) - Easily create Gravatar URLs in Gleam
* [aws4\_request](https://github.com/lpil/aws4_request) ⭐ 7 | 🐛 1 | 🌐 Gleam | 📅 2026-06-17 - [📚](https://hexdocs.pm/aws4_request/) - An AWS Signature Version 4 client implementation, used for S3 auth, etc
* [tallgrass](https://github.com/stevetoro/tallgrass) ⭐ 7 | 🐛 1 | 🌐 Gleam | 📅 2024-10-04 - [📚](https://hexdocs.pm/tallgrass/) - Gleam wrapper for the PokeAPI.
* [flwr\_oauth2](https://github.com/fweingartshofer/oauth) ⭐ 3 | 🐛 0 | 🌐 Gleam | 📅 2026-07-26 - [📚](https://hexdocs.pm/flwr_oauth2/) - An OAuth 2.0 Library based on Gleam types
* [gleam\_hexpm](https://github.com/gleam-lang/hexpm) ⭐ 3 | 🐛 1 | 🌐 Gleam | 📅 2025-04-05 - [📚](https://hexdocs.pm/gleam_hexpm/) - Gleam dynamic decoders for the API of Hex, the package manager for the BEAM ecosystem.
* [glatus](https://github.com/lpil/glatus) ⭐ 2 | 🐛 0 | 🌐 Gleam | 📅 2024-12-22 - [📚](https://hexdocs.pm/glatus/) - Gleam bindings to the API of the Gatus health check tool

### Benchmarking

* [glychee](https://github.com/inoas/glychee) ⭐ 22 | 🐛 5 | 🌐 Gleam | 📅 2026-05-23 - [📚](https://hexdocs.pm/glychee/) - Glychee: Easy access to Elixir's Benchee from Gleam!
* [gleamy\_bench](https://github.com/schurhammer/gleamy_bench) ⭐ 18 | 🐛 5 | 🌐 Gleam | 📅 2025-02-17 - [📚](https://hexdocs.pm/gleamy_bench/) - A library for benchmarking gleam code.

### Build Tooling

* [gleescript](https://github.com/lpil/gleescript) ⭐ 120 | 🐛 3 | 🌐 Gleam | 📅 2026-06-03 - [📚](https://hexdocs.pm/gleescript/) - Bundle your Gleam-on-Erlang project into an escript, a single executable file!
* [esgleam](https://github.com/Enderchief/esgleam) ⭐ 39 | 🐛 4 | 🌐 Gleam | 📅 2025-11-22 - [📚](https://hexdocs.pm/esgleam/) - esbuild for Gleam
* [gleamdoc](https://git.sr.ht/~jturner/gleamdoc) - [📚](https://hexdocs.pm/gleamdoc/) - Sparse, terminal-first documentation lookup for Gleam packages

### Command Line

* [glint](https://github.com/TanklesXL/glint) ⭐ 81 | 🐛 22 | 🌐 Gleam | 📅 2026-07-20 - [📚](https://hexdocs.pm/glint/) - Gleam command line argument parsing with basic flag support.
* [shellout](https://github.com/tynanbe/shellout) ⭐ 75 | 🐛 6 | 🌐 Gleam | 📅 2026-02-19 - [📚](https://hexdocs.pm/shellout/) - A Gleam library for cross-platform shell operations
* [rad](https://github.com/tynanbe/rad) ⭐ 72 | 🐛 1 | 🌐 Gleam | 📅 2024-06-14 - [📚](https://hexdocs.pm/rad/) - A task runner for Gleam projects
* [clip](https://github.com/drewolson/clip) ⭐ 52 | 🐛 0 | 🌐 Gleam | 📅 2026-08-19 - [📚](https://hexdocs.pm/clip/) - A CLI Option Parser for Gleam
* [argv](https://github.com/lpil/argv) ⭐ 42 | 🐛 2 | 🌐 Erlang | 📅 2026-05-11 - [📚](https://hexdocs.pm/argv/) - A cross platform library for getting the command line arguments
* [gleam\_community\_ansi](https://github.com/gleam-community/ansi) ⭐ 38 | 🐛 1 | 🌐 Gleam | 📅 2026-04-20 - [📚](https://hexdocs.pm/gleam_community_ansi/) - ANSI colours, formatting, and control codes
* [spinner](https://github.com/lpil/spinner) ⭐ 28 | 🐛 0 | 🌐 Gleam | 📅 2025-01-08 - [📚](https://hexdocs.pm/spinner/) - Animated progress spinners for your console
* [stdin](https://github.com/olian04/gleam-stdin) ⭐ 23 | 🐛 1 | 🌐 Shell | 📅 2025-05-27 - [📚](https://hexdocs.pm/stdin/) - Provides a synchronous iterator for consuming stdin. It supports all the non-browser targets, Erlang, Node, Deno, and Bun.
* [glitzer](https://github.com/miampf/glitzer) ⭐ 15 | 🐛 0 | 🌐 Gleam | 📅 2025-07-27 - [📚](https://hexdocs.pm/glitzer/) - Progress bars for gleam.

### Configuration

* [envoy](https://github.com/lpil/envoy) ⭐ 57 | 🐛 0 | 🌐 Gleam | 📅 2026-04-18 - [📚](https://hexdocs.pm/envoy/) - A zero dependency cross platform Gleam package for reading environment variables
* [dot\_env](https://github.com/aosasona/dotenv) ⭐ 40 | 🐛 3 | 🌐 Gleam | 📅 2026-07-25 - [📚](https://hexdocs.pm/dot_env/) - Load environment variables from files
* [glenvy](https://github.com/maxdeviant/glenvy) ⭐ 23 | 🐛 0 | 🌐 Gleam | 📅 2025-07-30 - [📚](https://hexdocs.pm/glenvy/) - A pleasant way to interact with your environment.
* [dotenv\_gleam](https://github.com/Grubba27/dotenv_gleam) ⭐ 14 | 🐛 3 | 🌐 Gleam | 📅 2025-10-13 - [📚](https://hexdocs.pm/dotenv_gleam/) - dotenv for Gleam
* [glenv](https://github.com/custompro98/glenv) ⭐ 2 | 🐛 0 | 🌐 Gleam | 📅 2025-04-25 - [📚](https://hexdocs.pm/glenv/) - A library for type-safe environment variable access.
* [k9\_gleam](https://github.com/hyperpolymath/k9_gleam) - [📚](https://hexdocs.pm/k9_gleam/) - Parser and renderer for K9 (Self-Validating Components), configuration with trust levels and Nickel contracts

### Cryptography

* [ids](https://github.com/rvcas/ids) ⭐ 60 | 🐛 3 | 🌐 Gleam | 📅 2025-01-26 - [📚](https://hexdocs.pm/ids/) - Unique IDs for Gleam
* [gleam\_crypto](https://github.com/gleam-lang/crypto) ⭐ 57 | 🐛 3 | 🌐 Gleam | 📅 2026-07-24 - [📚](https://hexdocs.pm/gleam_crypto/) - A Gleam cryptography library supporting Erlang and JavaScript
* [youid](https://github.com/lpil/youid) ⭐ 35 | 🐛 4 | 🌐 Gleam | 📅 2026-03-31 - [📚](https://hexdocs.pm/youid/) - Generate and parse UUIDs
* [argus](https://github.com/Pevensie/argus) ⭐ 27 | 🐛 0 | 🌐 Gleam | 📅 2026-04-26 - [📚](https://hexdocs.pm/argus/) - Argon2 password hashing library for Gleam, based on the reference C implementation.
* [kryptos](https://github.com/jtdowney/kryptos) ⭐ 18 | 🐛 0 | 🌐 Gleam | 📅 2026-08-05 - [📚](https://hexdocs.pm/kryptos/) - Comprehensive cryptography with AEAD ciphers, key derivation, and digital signatures for Erlang and JavaScript
* [beecrypt](https://github.com/lpil/beecrypt) ⭐ 10 | 🐛 1 | 🌐 Gleam | 📅 2025-05-14 - [📚](https://hexdocs.pm/beecrypt/) - Buzzing Gleam bindings to the Erlang bcrypt hashing library
* [acumen](https://github.com/jtdowney/acumen) ⭐ 6 | 🐛 0 | 🌐 Gleam | 📅 2026-08-14 - [📚](https://hexdocs.pm/acumen/) - ACME client for certificate management with Let's Encrypt and other ACME servers
* [kmh](https://github.com/mdarse/kmh) ⭐ 0 | 🐛 0 | 🌐 Gleam | 📅 2024-09-08 - [📚](https://hexdocs.pm/kmh/) - Implementation of Knuth’s multiplicative hashing (useful for ID obfuscation, etc.)

### Data Structures

* [gleam\_stdlib](https://github.com/gleam-lang/stdlib) ⭐ 706 | 🐛 33 | 🌐 Gleam | 📅 2026-08-18 - [📚](https://hexdocs.pm/gleam_stdlib/) - A standard library for the Gleam programming language
* [argamak](https://github.com/tynanbe/argamak) ⭐ 37 | 🐛 0 | 🌐 Gleam | 📅 2024-02-18 - [📚](https://hexdocs.pm/argamak/) - A tensor library for the Gleam programming language
* [gleamy\_structures](https://github.com/schurhammer/gleamy_structures/) ⭐ 33 | 🐛 1 | 🌐 Gleam | 📅 2025-08-25 - [📚](https://hexdocs.pm/gleamy_structures/) - Data structures in pure Gleam! Including tree, heap, non empty list, map, set, and priority queue.
* [act](https://github.com/MystPi/act) ⭐ 29 | 🐛 0 | 🌐 Gleam | 📅 2025-12-01 - [📚](https://hexdocs.pm/act/) - Compose stateful actions to simulate mutable state
* [trie\_again](https://github.com/giacomocavalieri/trie_again) ⭐ 15 | 🐛 0 | 🌐 Gleam | 📅 2025-09-09 - [📚](https://hexdocs.pm/trie_again/) - Tries in Gleam
* [non\_empty\_list](https://github.com/giacomocavalieri/non_empty_list) ⭐ 11 | 🐛 1 | 🌐 Gleam | 📅 2026-07-16 - [📚](https://hexdocs.pm/non_empty_list/) - Non-empty lists in Gleam
* [delay](https://github.com/bwireman/delay) ⭐ 10 | 🐛 0 | 🌐 Gleam | 📅 2026-04-26 - [📚](https://hexdocs.pm/delay/) - A dead simple data-structure for delaying side effects
* [glearray](https://github.com/fschwalbe/glearray) ⭐ 9 | 🐛 0 | 🌐 Gleam | 📅 2026-06-07 - [📚](https://hexdocs.pm/glearray/) - Immutable arrays for Gleam
* [tote](https://github.com/giacomocavalieri/tote) ⭐ 9 | 🐛 0 | 🌐 Gleam | 📅 2026-04-18 - [📚](https://hexdocs.pm/tote/) - Bags (or multisets) in Gleam
* [gleam\_zlists](https://github.com/mrdimosthenis/gleam_zlists) ⭐ 4 | 🐛 2 | 🌐 Gleam | 📅 2024-09-26 - [📚](https://hexdocs.pm/gleam_zlists/) - A library for working with lazy lists in Gleam
* [gleither](https://github.com/bwireman/gleither) ⭐ 3 | 🐛 0 | 🌐 Gleam | 📅 2025-12-20 - [📚](https://hexdocs.pm/gleither/) - A small data-structure for representing an Either Monad
* [iv](https://gitlab.com/arkandos/iv) - [📚](https://hexdocs.pm/iv/) - A fast, safe, batteries-included array for Gleam!

### Databases

* [squirrel](https://github.com/giacomocavalieri/squirrel) ⭐ 679 | 🐛 13 | 🌐 Gleam | 📅 2026-08-18 - [📚](https://hexdocs.pm/squirrel/) - 🐿️ Type safe SQL in Gleam
* [pog](https://github.com/lpil/pog) ⭐ 264 | 🐛 19 | 🌐 Gleam | 📅 2026-03-09 - [📚](https://hexdocs.pm/pog/) - A PostgreSQL database client for Gleam, based on PGO
* [parrot](https://github.com/daniellionel01/parrot) ⭐ 214 | 🐛 8 | 🌐 Gleam | 📅 2026-08-18 - [📚](https://hexdocs.pm/parrot/) - 🦜 type-safe SQL in gleam via sqlc
* [sqlight](https://github.com/lpil/sqlight) ⭐ 155 | 🐛 7 | 🌐 Gleam | 📅 2026-07-10 - [📚](https://hexdocs.pm/sqlight/) - Use SQLite from Gleam!
* [cake](https://github.com/inoas/gleam-cake) ⭐ 132 | 🐛 2 | 🌐 Gleam | 📅 2026-06-06 - [📚](https://hexdocs.pm/cake/) - An SQL query builder for dialects PostgreSQL, SQLite, MariaDB, and MySQL
* [radish](https://github.com/massivefermion/radish) ⭐ 47 | 🐛 8 | 🌐 Gleam | 📅 2025-01-25 - [📚](https://hexdocs.pm/radish/) - A Redis client for Gleam
* [valkyrie](https://github.com/Pevensie/valkyrie) ⭐ 45 | 🐛 1 | 🌐 Gleam | 📅 2026-05-16 - [📚](https://hexdocs.pm/valkyrie/) - A lightweight, performant Redis-compatible client for Gleam
* [storail](https://github.com/lpil/storail) ⭐ 41 | 🐛 0 | 🌐 Gleam | 📅 2026-07-18 - [📚](https://hexdocs.pm/storail/) - A simple on-disc JSON based data store
* [mungo](https://github.com/massivefermion/mungo) ⭐ 26 | 🐛 2 | 🌐 Gleam | 📅 2024-12-20 - [📚](https://hexdocs.pm/mungo/) - A MongoDB driver for Gleam (formerly gleam\_mongo)
* [migrant](https://github.com/aosasona/migrant) ⭐ 20 | 🐛 5 | 🌐 Gleam | 📅 2026-06-14 - [📚](https://hexdocs.pm/migrant/) - Database migrations for SQLite in Gleam

### Email

* [gcourier](https://github.com/gideongrinberg/gcourier) ⭐ 17 | 🐛 8 | 🌐 Gleam | 📅 2026-04-19 - [📚](https://hexdocs.pm/gcourier/) - Send emails from Gleam using SMTP
* [gleam\_sendgrid](https://github.com/lpil/gleam_sendgrid) ⭐ 15 | 🐛 0 | 🌐 Gleam | 📅 2026-04-19 - [📚](https://hexdocs.pm/gleam_sendgrid/) - Send emails from Gleam with SendGrid
* [plunk](https://github.com/aosasona/plunk.gleam) ⭐ 12 | 🐛 2 | 🌐 Gleam | 📅 2025-06-04 - [📚](https://hexdocs.pm/plunk/) - A Gleam library to send emails, manage contacts etc. using the Plunk API
* [zeptomail](https://github.com/lpil/zeptomail) ⭐ 7 | 🐛 0 | 🌐 Gleam | 📅 2025-12-28 - [📚](https://hexdocs.pm/zeptomail/) - A wrapper for ZeptoMail's transactional email API

### Erlang and OTP

* [gleam\_otp](https://github.com/gleam-lang/otp) ⭐ 870 | 🐛 8 | 🌐 Gleam | 📅 2026-08-09 - [📚](https://hexdocs.pm/gleam_otp/) - Fault tolerant multicore Gleam programs with OTP
* [gleam\_erlang](https://github.com/gleam-lang/erlang) ⭐ 134 | 🐛 10 | 🌐 Gleam | 📅 2026-07-22 - [📚](https://hexdocs.pm/gleam_erlang/) - A Gleam library for working with Erlang
* [spectator](https://github.com/JonasGruenwald/spectator) ⭐ 98 | 🐛 4 | 🌐 Gleam | 📅 2026-04-21 - [📚](https://hexdocs.pm/spectator/) - A BEAM runtime observer tool
* [barnacle](https://github.com/Pevensie/barnacle) ⭐ 59 | 🐛 1 | 🌐 Gleam | 📅 2025-06-14 - [📚](https://hexdocs.pm/barnacle/) - Self-healing clusters for Gleam applications on the BEAM
* [Eventsourcing](https://github.com/renatillas/eventsourcing) ⭐ 49 | 🐛 1 | 🌐 HTML | 📅 2025-10-18 - [📚](https://hexdocs.pm/Eventsourcing/) - A Gleam library for building event-sourced systems with Actors and Supervisors
* [chip](https://github.com/chouzar/chip) ⭐ 31 | 🐛 5 | 🌐 Gleam | 📅 2024-12-14 - [📚](https://hexdocs.pm/chip/) - A Gleam registry library
* [carpenter](https://github.com/grottohub/carpenter) ⭐ 30 | 🐛 3 | 🌐 Gleam | 📅 2024-04-08 - [📚](https://hexdocs.pm/carpenter/) - Bindings for Erlang's ETS tables. Forked and updated from gts.
* [bath](https://github.com/Pevensie/bath) ⭐ 22 | 🐛 0 | 🌐 Gleam | 📅 2026-02-20 - [📚](https://hexdocs.pm/bath/) - A generic resource pool
* [lifeguard](https://github.com/Pevensie/lifeguard) ⭐ 19 | 🐛 0 | 🌐 Gleam | 📅 2025-06-25 - [📚](https://hexdocs.pm/lifeguard/) - A simple actor pool
* [shakespeare](https://github.com/maxdeviant/shakespeare) ⭐ 16 | 🐛 2 | 🌐 Gleam | 📅 2024-12-07 - [📚](https://hexdocs.pm/shakespeare/) - General-purpose OTP actors.
* [nessie\_cluster](https://github.com/ckreiling/nessie_cluster) ⭐ 13 | 🐛 1 | 🌐 Gleam | 📅 2025-01-27 - [📚](https://hexdocs.pm/nessie_cluster/) - A small DNS clustering library for Gleam applications.
* [puddle](https://github.com/massivefermion/puddle) ⭐ 7 | 🐛 2 | 🌐 Gleam | 📅 2024-12-04 - [📚](https://hexdocs.pm/puddle/) - A resource pool manager for gleam
* [process\_waiter](https://github.com/lpil/process-waiter) ⭐ 3 | 🐛 0 | 🌐 Gleam | 📅 2024-01-02 - [📚](https://hexdocs.pm/process_waiter/) - Wait for Erlang processes to exit
* [gen\_core\_erlang](https://codeberg.org/kero/gleam_codegen) - [📚](https://hexdocs.pm/gen_core_erlang/) - Generate Core Erlang from Gleam (wraps the Erlang cerl compiler module)

### Error Handling

* [snag](https://github.com/gleam-experiments/snag) ⭐ 81 | 🐛 1 | 🌐 Gleam | 📅 2025-11-02 - [📚](https://hexdocs.pm/snag/) - A boilerplate-free ad-hoc error type
* [exception](https://github.com/lpil/exception) ⭐ 11 | 🐛 0 | 🌐 Gleam | 📅 2026-06-24 - [📚](https://hexdocs.pm/exception/) - A tiny package for dealing with exceptions

### File System

* [simplifile](https://github.com/bcpeinhardt/simplifile) ⭐ 143 | 🐛 2 | 🌐 Gleam | 📅 2026-08-05 - [📚](https://hexdocs.pm/simplifile/) - Basic file operations that work on all targets
* [file\_streams](https://github.com/richard-viney/file_streams) ⭐ 54 | 🐛 2 | 🌐 Gleam | 📅 2026-05-01 - [📚](https://hexdocs.pm/file_streams/) - Gleam library that provides access to native Erlang binary file streams.
* [filepath](https://github.com/lpil/filepath) ⭐ 34 | 🐛 5 | 🌐 Gleam | 📅 2025-04-01 - [📚](https://hexdocs.pm/filepath/) - Work with file paths in Gleam!

### Formats

* [jot](https://github.com/lpil/jot) ⭐ 63 | 🐛 6 | 🌐 Gleam | 📅 2026-08-12 - [📚](https://hexdocs.pm/jot/) - A parser for Djot, a markdown-like language
* [tom](https://github.com/lpil/tom) ⭐ 40 | 🐛 5 | 🌐 Gleam | 📅 2026-04-30 - [📚](https://hexdocs.pm/tom/) - A pure Gleam TOML parser!
* [commonmark](https://github.com/mscharley/gleam-commonmark) ⭐ 32 | 🐛 14 | 🌐 Gleam | 📅 2026-08-07 - [📚](https://hexdocs.pm/commonmark/) - CommonMark implementation for Gleam, for the BEAM or JS
* [cymbal](https://github.com/lpil/cymbal) ⭐ 20 | 🐛 2 | 🌐 Gleam | 📅 2026-03-09 - [📚](https://hexdocs.pm/cymbal/) - Build YAML in Gleam!
* [xmb](https://github.com/lpil/xmb) ⭐ 12 | 🐛 0 | 🌐 Gleam | 📅 2025-04-06 - [📚](https://hexdocs.pm/xmb/) - A tiny XML builder for Gleam
* [gsv](https://github.com/bcpeinhardt/gsv) ⭐ 0 | 🐛 0 | 📅 2025-08-29 - [📚](https://hexdocs.pm/gsv/) - A simple csv parser and generator written in gleam
* [iso\_8859](https://github.com/richard-viney/iso_8859) ⚠️ Archived - [📚](https://hexdocs.pm/iso_8859/) - Gleam library to decode ISO/IEC 8859 binary data into native UTF-8 strings.
* [a2ml\_gleam](https://github.com/hyperpolymath/a2ml_gleam) - [📚](https://hexdocs.pm/a2ml_gleam/) - Parser and renderer for A2ML (Attested Markup Language), an AI agent identity and attestation format
* [mork](https://hex.pm/packages/mork) - [📚](https://hexdocs.pm/mork/) - A Markdown (CommonMark/GFM/OFM) parser in pure Gleam

### Frontend

* [lustre](https://github.com/lustre-labs/lustre) ⭐ 2,412 | 🐛 21 | 🌐 Gleam | 📅 2026-08-05 - [📚](https://hexdocs.pm/lustre/) - An Elm-inspired framework for building web apps in Gleam!
* [lustre\_ui](https://github.com/lustre-labs/lustre_ui) ⭐ 171 | 🐛 5 | 🌐 Gleam | 📅 2026-05-26 - [📚](https://hexdocs.pm/lustre_ui/) - A collection of components and design tokens for building Lustre apps.
* [tiramisu](https://github.com/renatillas/tiramisu) ⚠️ Archived - [📚](https://hexdocs.pm/tiramisu/) - A type-safe 3D game engine for Gleam
* [sketch](https://github.com/ghivert/sketch) ⭐ 85 | 🐛 9 | 🌐 Gleam | 📅 2026-04-22 - [📚](https://hexdocs.pm/sketch/) - A CSS-in-Gleam package, made to work with frontend, and directly with lustre!
* [redraw](https://github.com/ghivert/redraw) ⭐ 74 | 🐛 1 | 🌐 Gleam | 📅 2026-04-30 - [📚](https://hexdocs.pm/redraw/) - React bindings for Gleam! Supports everything modern React provides, with full Gleam Type-Checking system!
* [glailglind](https://github.com/okkdev/glailglind) ⭐ 49 | 🐛 0 | 🌐 Gleam | 📅 2026-04-20 - [📚](https://hexdocs.pm/glailglind/) - Gleam modules and functions for installing and invoking TailwindCSS
* [tardis](https://github.com/ghivert/tardis) ⚠️ Archived - [📚](https://hexdocs.pm/tardis/) - Time traveller debugger, tailor-made for Lustre
* [grille\_pain](https://github.com/ghivert/grille-pain) ⭐ 24 | 🐛 0 | 🌐 Gleam | 📅 2026-04-22 - [📚](https://hexdocs.pm/grille_pain/) - Toaster, made in lustre, for gleam
* [lustre\_virtual\_list](https://github.com/schurhammer/lustre_virtual_list) ⭐ 14 | 🐛 0 | 🌐 Gleam | 📅 2024-10-28 - [📚](https://hexdocs.pm/lustre_virtual_list/) - A virtual list component for lustre.
* [lustre\_animation](https://git.chmeee.org/lustre_animation) - [📚](https://hexdocs.pm/lustre_animation/) - Animations for lustre, utilizing JS requestAnimationFrame and setTimeout
* [lustre\_http](https://codeberg.org/kero/lustre_http) - [📚](https://hexdocs.pm/lustre_http/) - HTTP requests from lustre
* [lustre\_websocket](https://codeberg.org/kero/lustre_websocket) - [📚](https://hexdocs.pm/lustre_websocket/) - Web Socket requests from lustre

### Gleam

* [glance](https://github.com/lpil/glance) ⭐ 80 | 🐛 3 | 🌐 Gleam | 📅 2026-07-09 - [📚](https://hexdocs.pm/glance/) - A Gleam source code parser, in Gleam!
* [glexer](https://github.com/DanielleMaywood/glexer) ⭐ 65 | 🐛 0 | 🌐 Gleam | 📅 2026-08-03 - [📚](https://hexdocs.pm/glexer/) - A lexer for Gleam source code
* [pprint](https://github.com/MystPi/pprint) ⭐ 43 | 🐛 0 | 🌐 Gleam | 📅 2025-07-07 - [📚](https://hexdocs.pm/pprint/) - Pretty print values with style!
* [gleam\_package\_interface](https://github.com/gleam-lang/package-interface-decoder) ⭐ 11 | 🐛 1 | 🌐 Gleam | 📅 2025-05-13 - [📚](https://hexdocs.pm/gleam_package_interface/) - Work with Gleam's package interfaces
* [glance\_printer](https://github.com/bcpeinhardt/glance_printer) ⭐ 7 | 🐛 2 | 🌐 Gleam | 📅 2025-05-03 - [📚](https://hexdocs.pm/glance_printer/) - A pretty\_printer for the glance AST

### Graphics

* [gleam\_community\_colour](https://github.com/gleam-community/colour) ⭐ 22 | 🐛 3 | 🌐 Gleam | 📅 2026-04-20 - [📚](https://hexdocs.pm/gleam_community_colour/) - Colour types, conversions, and other utilities
* [ansel](https://github.com/tinybackup/ansel) ⭐ 7 | 🐛 0 | 🌐 Gleam | 📅 2025-07-30 - [📚](https://hexdocs.pm/ansel/) - A simple and fast vips image processing library for Gleam!

### HTML

* [nakai](https://github.com/nakaixo/nakai) ⭐ 138 | 🐛 3 | 🌐 Gleam | 📅 2025-08-04 - [📚](https://hexdocs.pm/nakai/) - HTML generation for Gleam, on the server or anywhere else
* [formal](https://github.com/lpil/formal) ⭐ 54 | 🐛 2 | 🌐 Gleam | 📅 2026-07-25 - [📚](https://hexdocs.pm/formal/) - Type safe HTML form decoding and validation!
* [htmb](https://github.com/lpil/htmb) ⭐ 21 | 🐛 0 | 🌐 Gleam | 📅 2024-12-07 - [📚](https://hexdocs.pm/htmb/) - A tiny HTML builder for Gleam
* [houdini](https://github.com/giacomocavalieri/houdini) ⭐ 14 | 🐛 0 | 🌐 Gleam | 📅 2026-04-18 - [📚](https://hexdocs.pm/houdini/) - 🪄 Fast HTML escaping
* [htmgrrrl](https://github.com/lpil/htmgrrrl) ⭐ 14 | 🐛 1 | 🌐 Gleam | 📅 2026-07-23 - [📚](https://hexdocs.pm/htmgrrrl/) - Gleam bindings to htmerl, the fast and memory efficient Erlang HTML SAX parser.
* [odysseus](https://github.com/strawmelonjuice/odysseus) ⭐ 2 | 🐛 0 | 🌐 Erlang | 📅 2025-05-24 - [📚](https://hexdocs.pm/odysseus/) - UN-escaping HTML
* [glentities](https://gitlab.com/Nicd/glentities) - [📚](https://hexdocs.pm/glentities/) - HTML entity encoder/decoder for Gleam

### HTTP

* [gleam\_http](https://github.com/gleam-lang/http) ⭐ 284 | 🐛 5 | 🌐 Gleam | 📅 2025-10-02 - [📚](https://hexdocs.pm/gleam_http/) - Types and functions for Gleam HTTP clients and servers
* [cors\_builder](https://github.com/ghivert/cors-builder) ⭐ 18 | 🐛 0 | 🌐 Gleam | 📅 2026-04-22 - [📚](https://hexdocs.pm/cors_builder/) - A CORS Builder, performing validation and injection of CORS for misp, wisp and any framework!

### HTTP Clients

* [gleam\_httpc](https://github.com/gleam-lang/httpc) ⭐ 173 | 🐛 19 | 🌐 Gleam | 📅 2026-08-10 - [📚](https://hexdocs.pm/gleam_httpc/) - Gleam bindings to Erlang's built in HTTP client, httpc
* [gleam\_hackney](https://github.com/gleam-lang/hackney) ⭐ 62 | 🐛 8 | 🌐 Gleam | 📅 2026-05-26 - [📚](https://hexdocs.pm/gleam_hackney/) - Gleam bindings to the Hackney HTTP client
* [gleam\_fetch](https://github.com/gleam-lang/fetch) ⭐ 61 | 🐛 5 | 🌐 Gleam | 📅 2026-04-02 - [📚](https://hexdocs.pm/gleam_fetch/) - Make HTTP requests in Gleam JavaScript with Fetch

### HTTP Servers

* [mist](https://github.com/rawhat/mist) ⭐ 522 | 🐛 9 | 🌐 Gleam | 📅 2026-04-18 - [📚](https://hexdocs.pm/mist/) - a misty Gleam web server
* [ewe](https://github.com/vshakitskiy/ewe) ⭐ 123 | 🐛 2 | 🌐 Gleam | 📅 2026-08-19 - [📚](https://hexdocs.pm/ewe/) - 🐑 a fluffy Gleam web server
* [gleam\_elli](https://github.com/gleam-lang/elli) ⭐ 74 | 🐛 1 | 🌐 Gleam | 📅 2025-06-02 - [📚](https://hexdocs.pm/gleam_elli/) - Run Gleam HTTP services with the Elli web server
* [cgi](https://github.com/lpil/cgi) ⭐ 17 | 🐛 0 | 🌐 Gleam | 📅 2024-01-16 - [📚](https://hexdocs.pm/cgi/) - Common Gateway Interface (CGI) in Gleam

### JSON

* [gleam\_json](https://github.com/gleam-lang/json) ⭐ 150 | 🐛 4 | 🌐 Gleam | 📅 2026-05-04 - [📚](https://hexdocs.pm/gleam_json/) - Work with JSON in Gleam
* [json\_typedef](https://github.com/lpil/json-typedef) ⭐ 50 | 🐛 3 | 🌐 Gleam | 📅 2026-04-19 - [📚](https://hexdocs.pm/json_typedef/) - Work with JSON using a schema! RFC8927
* [squirtle](https://github.com/alii/squirtle) ⭐ 11 | 🐛 0 | 🌐 Gleam | 📅 2026-07-29 - [📚](https://hexdocs.pm/squirtle/) - A JSON Patch (RFC 6902) implementation in Gleam

### JavaScript

* [plinth](https://github.com/Crowdhailer/plinth) ⭐ 118 | 🐛 4 | 🌐 Gleam | 📅 2026-08-11 - [📚](https://hexdocs.pm/plinth/) - Bindings to Node.js and browser platform APIs
* [gleam\_javascript](https://github.com/gleam-lang/javascript) ⭐ 79 | 🐛 2 | 🌐 Gleam | 📅 2026-07-09 - [📚](https://hexdocs.pm/gleam_javascript/) - Work with JavaScript types and values in Gleam
* [conversation](https://github.com/MystPi/conversation) ⭐ 19 | 🐛 1 | 🌐 Gleam | 📅 2025-06-30 - [📚](https://hexdocs.pm/conversation/) - Gleam bindings for the standard JavaScript Request and Response APIs
* [javascript\_dom\_parser](https://github.com/lpil/javascript-dom-parser) ⭐ 7 | 🐛 2 | 🌐 Gleam | 📅 2024-04-07 - [📚](https://hexdocs.pm/javascript_dom_parser/) - Bindings to the JavaScript DOMParser API

### Logging and Monitoring

* [glimt](https://github.com/JohnBjrk/glimt) ⭐ 31 | 🐛 1 | 🌐 Gleam | 📅 2024-03-19 - [📚](https://hexdocs.pm/glimt/) - A Gleam library for logging
* [logging](https://github.com/lpil/logging) ⭐ 12 | 🐛 0 | 🌐 Erlang | 📅 2026-04-03 - [📚](https://hexdocs.pm/logging/) - Configuration for the Erlang logger
* [glog](https://github.com/defgenx/glog) ⭐ 11 | 🐛 0 | 🌐 Gleam | 📅 2024-04-12 - [📚](https://hexdocs.pm/glog/) - A Gleam implementation of Erlang logger
* [stacky](https://github.com/inoas/stacky) ⭐ 11 | 🐛 2 | 🌐 Gleam | 📅 2024-06-06 - [📚](https://hexdocs.pm/stacky/) - Stacky ☆ BEAM stack trace in Gleam
* [systemd\_status](https://github.com/lpil/systemd_status) ⭐ 8 | 🐛 0 | 🌐 Gleam | 📅 2026-05-30 - [📚](https://hexdocs.pm/systemd_status/) - Inspect the status of running systemd units

### Machine Learning

* [emel](https://github.com/mrdimosthenis/emel) ⭐ 115 | 🐛 0 | 🌐 Gleam | 📅 2024-09-26 - [📚](https://hexdocs.pm/emel/) - Turn data into functions in the Erlang ecosystem
* [gleam\_synapses](https://github.com/mrdimosthenis/gleam_synapses) ⭐ 43 | 🐛 0 | 🌐 Gleam | 📅 2024-09-26 - [📚](https://hexdocs.pm/gleam_synapses/) - A plug-and-play library for neural networks written in Gleam

### Networking

* [glisten](https://github.com/rawhat/glisten) ⭐ 98 | 🐛 11 | 🌐 Gleam | 📅 2026-06-27 - [📚](https://hexdocs.pm/glisten/) - a shiny Gleam TCP/SSL server
* [mug](https://github.com/lpil/mug) ⭐ 36 | 🐛 4 | 🌐 Gleam | 📅 2025-09-09 - [📚](https://hexdocs.pm/mug/) - A TCP client for Gleam!
* [nessie](https://github.com/ckreiling/nessie) ⭐ 8 | 🐛 2 | 🌐 Gleam | 📅 2024-04-07 - [📚](https://hexdocs.pm/nessie/) - Gleam bindings for Erlang's built-in DNS resolution modules.
* [ftpasta](https://codeberg.org/Deepfriedice/FTPasta) - [📚](https://hexdocs.pm/ftpasta/) - A simple to use wrapper around Erlang's built-in ftp module.

### Numbers

* [gleam\_community\_maths](https://github.com/gleam-community/maths) ⭐ 49 | 🐛 4 | 🌐 Gleam | 📅 2026-04-20 - [📚](https://hexdocs.pm/gleam_community_maths/) - A basic maths library
* [bigdecimal](https://github.com/horvathandris/bigdecimal) ⭐ 8 | 🐛 2 | 🌐 Gleam | 📅 2026-01-01 - [📚](https://hexdocs.pm/bigdecimal/) - Arbitrary precision decimal arithmetic for Gleam
* [bigi](https://gitlab.com/Nicd/bigi) - [📚](https://hexdocs.pm/bigi/) - Arbitrary precision integer arithmetic for Gleam
* [vec](https://codeberg.org/gwg/vec) - [📚](https://hexdocs.pm/vec/) - A vectors library for the Gleam programming language

### Parsing

* [nibble](https://github.com/hayleigh-dot-dev/gleam-nibble) ⭐ 91 | 🐛 5 | 🌐 Gleam | 📅 2025-07-29 - [📚](https://hexdocs.pm/nibble/) - A string parsing library heavily inspired by elm/parser.
* [gleamsver](https://github.com/aznashwan/gleamsver) ⭐ 2 | 🐛 0 | 🌐 Gleam | 📅 2024-07-08 - [📚](https://hexdocs.pm/gleamsver/) - Comprehensive set of native Gleam utilities for handling SemVer 2.0.0 version strings.
* [stoiridh\_version](https://gitlab.com/stoiridh-project/stoiridh-version) - [📚](https://hexdocs.pm/stoiridh_version/) - Semantic Versioning 2.0.0

### Project Tooling

* [go\_over](https://github.com/bwireman/go-over) ⭐ 26 | 🐛 1 | 🌐 Gleam | 📅 2026-06-21 - [📚](https://hexdocs.pm/go_over/) - A tool to audit Erlang & Elixir dependencies, to make sure your gleam projects really sparkle! ✨
* [cactus](https://github.com/bwireman/cactus) ⭐ 20 | 🐛 1 | 🌐 Gleam | 📅 2026-06-20 - [📚](https://hexdocs.pm/cactus/) - A tool for managing git lifecycle hooks with ✨ gleam! Pre commit, Pre push and more!
* [hexdocs\_offline](https://github.com/daniellionel01/hexdocs_offline) ⭐ 10 | 🐛 2 | 🌐 Gleam | 📅 2026-04-29 - [📚](https://hexdocs.pm/hexdocs_offline/) - Download an offline version of the hexdocs of your projects dependencies to a local folder!

### Push Notifications

* [wimp](https://github.com/lpil/wimp-pushover) ⭐ 8 | 🐛 0 | 🌐 Gleam | 📅 2025-04-27 - [📚](https://hexdocs.pm/wimp/) - A Gleam client for the Pushover push notification API
* [webpush](https://github.com/imlargo/gleam-webpush) ⭐ 3 | 🐛 0 | 🌐 Gleam | 📅 2025-08-26 - [📚](https://hexdocs.pm/webpush/) - Web Push API library for Gleam, supports encryption and VAPID

### Queues and Job Processing

* [m25](https://github.com/Pevensie/m25) ⭐ 34 | 🐛 1 | 🌐 Gleam | 📅 2026-01-01 - [📚](https://hexdocs.pm/m25/) - A background job library for Gleam and Postgres!
* [Carotte](https://github.com/renatillas/carotte) ⭐ 31 | 🐛 0 | 🌐 Gleam | 📅 2026-01-12 - [📚](https://hexdocs.pm/Carotte/) - A RabbitMQ client for Gleam
* [Franz](https://github.com/renatillas/franz) ⭐ 10 | 🐛 0 | 🌐 Gleam | 📅 2026-01-12 - [📚](https://hexdocs.pm/Franz/) - A Kafka client for Gleam

### Randomness

* [prng](https://github.com/giacomocavalieri/prng) ⭐ 33 | 🐛 1 | 🌐 Gleam | 📅 2026-06-26 - [📚](https://hexdocs.pm/prng/) - A Pure Random Number Generator
* [blah](https://github.com/massivefermion/blah) ⭐ 21 | 🐛 3 | 🌐 Gleam | 📅 2024-12-19 - [📚](https://hexdocs.pm/blah/) - fake data generation for gleam
* [minigen](https://github.com/mrdimosthenis/minigen) ⭐ 19 | 🐛 2 | 🌐 Gleam | 📅 2024-09-26 - [📚](https://hexdocs.pm/minigen/) - Pure random data generation, appropriate for realistic simulations

### SDKs

* [bucket](https://github.com/lpil/bucket) ⭐ 45 | 🐛 1 | 🌐 Gleam | 📅 2026-07-06 - [📚](https://hexdocs.pm/bucket/) - Gleam S3 API client, suitable for AWS S3, Garage, Minio, Storj, Backblaze B2, Cloudflare R2, Ceph, Wasabi, and so on!
* [openfeature](https://github.com/horvathandris/openfeature-gleam-sdk) ⭐ 5 | 🐛 2 | 🌐 Gleam | 📅 2025-11-24 - [📚](https://hexdocs.pm/openfeature/) - The Gleam SDK for the OpenFeature specification.
* [wechat\_dev\_tools](https://github.com/kaiwu/wechat_dev_tools) ⭐ 1 | 🐛 0 | 🌐 Less | 📅 2026-03-17 - [📚](https://hexdocs.pm/wechat_dev_tools/) - Tools to develop wechat miniprogram in gleam
* [weapp](https://github.com/kaiwu/weapp) ⭐ 0 | 🐛 0 | 🌐 Gleam | 📅 2026-08-02 - [📚](https://hexdocs.pm/weapp/) - Gleam bindings for wechat miniprogram, a.k.a weapp

### Standards

* [marceau](https://github.com/lpil/marceau) ⭐ 14 | 🐛 0 | 🌐 Gleam | 📅 2024-10-18 - [📚](https://hexdocs.pm/marceau/) - A MIME types library for Gleam
* [dime](https://github.com/horvathandris/dime) ⭐ 13 | 🐛 1 | 🌐 Gleam | 📅 2026-07-20 - [📚](https://hexdocs.pm/dime/) - A ISO-4217 currency library for Gleam
* [phony](https://github.com/massivefermion/phony) ⭐ 11 | 🐛 0 | 🌐 Gleam | 📅 2026-02-22 - [📚](https://hexdocs.pm/phony/) - An international phone number validator
* [glisbn](https://github.com/solar05/glisbn) ⭐ 4 | 🐛 0 | 🌐 Gleam | 📅 2026-05-21 - [📚](https://hexdocs.pm/glisbn/) - A ISBN utility library for Gleam.
* [thirtytwo](https://github.com/jtdowney/thirtytwo) ⭐ 1 | 🐛 0 | 🌐 Gleam | 📅 2026-08-01 - [📚](https://hexdocs.pm/thirtytwo/) - Base32 encoding and decoding

### TUI

* [etch](https://github.com/bananaofhappiness/etch) ⭐ 51 | 🐛 0 | 🌐 Gleam | 📅 2026-06-29 - [📚](https://hexdocs.pm/etch/) - Gleam terminal backend library

### Templating

* [glemplate](https://git.ahlcode.fi/nicd/glemplate) - [📚](https://hexdocs.pm/glemplate/) - A simple template engine for Gleam
* [handles](https://github.com/olian04/gleam_handles) ⭐ 24 | 🐛 1 | 🌐 Gleam | 📅 2026-04-20 - [📚](https://hexdocs.pm/handles/) - Pure Gleam templating language inspired by Mustache and Handlebars.js

### Testing

* [birdie](https://github.com/giacomocavalieri/birdie) ⭐ 202 | 🐛 1 | 🌐 Gleam | 📅 2026-07-17 - [📚](https://hexdocs.pm/birdie/) - Snapshot testing in Gleam
* [gleeunit](https://github.com/lpil/gleeunit) ⭐ 47 | 🐛 14 | 🌐 Gleam | 📅 2026-06-07 - [📚](https://hexdocs.pm/gleeunit/) - Gleam bindings to Erlang's EUnit test framework
* [testcontainers\_gleam](https://github.com/darky/testcontainers-gleam) ⭐ 8 | 🐛 0 | 🌐 Gleam | 📅 2026-02-15 - [📚](https://hexdocs.pm/testcontainers_gleam/) - Gleam TestContainers wrapper around Elixir TestContainers
* [exercism\_test\_runner](https://github.com/exercism/gleam-test-runner) ⭐ 6 | 🐛 8 | 🌐 Gleam | 📅 2026-08-01 - [📚](https://hexdocs.pm/exercism_test_runner/) - A test framework for Gleam exercises on Exercism
* [unitest](https://github.com/jtdowney/unitest) ⭐ 6 | 🐛 0 | 🌐 Gleam | 📅 2026-08-01 - [📚](https://hexdocs.pm/unitest/) - A test runner with random ordering, tagging, and CLI filtering
* [testbldr](https://github.com/bcpeinhardt/testbldr) ⭐ 4 | 🐛 1 | 🌐 Gleam | 📅 2024-02-01 - [📚](https://hexdocs.pm/testbldr/) - A library for programatically building and running test cases

### Text

* [rank](https://github.com/lpil/glance) ⭐ 80 | 🐛 3 | 🌐 Gleam | 📅 2026-07-09 - [📚](https://hexdocs.pm/rank/) - Ordinals for numbers, e.g. 1st, 2nd, 3rd
* [glam](https://github.com/giacomocavalieri/glam) ⭐ 68 | 🐛 0 | 🌐 Gleam | 📅 2026-04-20 - [📚](https://hexdocs.pm/glam/) - A package to help you easily pretty print structured data
* [hug](https://github.com/brettkolodny/gleam-hug) ⭐ 33 | 🐛 0 | 🌐 Gleam | 📅 2024-05-01 - [📚](https://hexdocs.pm/hug/) - Helpful and pretty CLI messages
* [g18n](https://github.com/renatillas/g18n) ⭐ 29 | 🐛 1 | 🌐 Gleam | 📅 2025-12-07 - [📚](https://hexdocs.pm/g18n/) - A platform-agnostic internationalization library for Gleam.
* [gap](https://github.com/JohnBjrk/gap) ⭐ 20 | 🐛 1 | 🌐 Gleam | 📅 2024-03-16 - [📚](https://hexdocs.pm/gap/) - A Gleam library for comparing strings/lists and producing a textual (styled) representation of the differences.
* [str](https://github.com/lupodevelop/str) ⭐ 11 | 🐛 0 | 🌐 Gleam | 📅 2026-04-22 - [📚](https://hexdocs.pm/str/) - Unicode-aware string utilities for Gleam
* [edit\_distance](https://github.com/giacomocavalieri/edit_distance) ⭐ 10 | 🐛 3 | 🌐 Gleam | 📅 2026-02-20 - [📚](https://hexdocs.pm/edit_distance/) - A pure Gleam package to compute the edit distance of two strings
* [justin](https://github.com/lpil/justin) ⭐ 10 | 🐛 0 | 🌐 Gleam | 📅 2026-04-18 - [📚](https://hexdocs.pm/justin/) - Convert between snake\_case, camelCase, and other cases in Gleam
* [humanise](https://github.com/SaphiraKai/humanise) ⭐ 8 | 🐛 0 | 🌐 Gleam | 📅 2025-08-29 - [📚](https://hexdocs.pm/humanise/) - Easily format values for human readability!
* [wink](https://github.com/MAHcodes/wink) ⭐ 7 | 🐛 0 | 🌐 Gleam | 📅 2024-04-13 - [📚](https://hexdocs.pm/wink/) - A simple Gleam box drawing library
* [dedent](https://github.com/MystPi/dedent) ⭐ 4 | 🐛 0 | 🌐 Gleam | 📅 2024-04-20 - [📚](https://hexdocs.pm/dedent/) - Remove shared indentation from a string
* [phonetic\_gleam](https://github.com/leobm/phonetic_gleam) ⭐ 3 | 🐛 0 | 🌐 Gleam | 📅 2024-03-08 - [📚](https://hexdocs.pm/phonetic_gleam/) - A collection of gleam algorithms dealing with phonetics.
* [punycode](https://codeberg.org/sotolf/gleam_punycode/) - [📚](https://hexdocs.pm/punycode/) - Gleam implementation of punycode encoding and decoding

### Time

* [birl](https://github.com/massivefermion/birl) ⭐ 86 | 🐛 11 | 🌐 Gleam | 📅 2026-02-23 - [📚](https://hexdocs.pm/birl/) - Date / Time handling for Gleam
* [gleam\_time](https://github.com/gleam-lang/time) ⭐ 69 | 🐛 3 | 🌐 Gleam | 📅 2026-08-13 - [📚](https://hexdocs.pm/gleam_time/) - Work with time in Gleam!
* [gtempo](https://github.com/jrstrunk/tempo) ⭐ 51 | 🐛 0 | 🌐 Gleam | 📅 2026-07-29 - [📚](https://hexdocs.pm/gtempo/) - A lightweight and Gleamy datetime library!
* [Clockwork](https://github.com/renatillas/clockwork) ⭐ 23 | 🐛 0 | 🌐 Gleam | 📅 2025-10-18 - [📚](https://hexdocs.pm/Clockwork/) - A cron expression parser library for Gleam
* [rada](https://github.com/michaeljones/rada) ⭐ 16 | 🐛 0 | 🌐 Gleam | 📅 2025-12-16 - [📚](https://hexdocs.pm/rada/) - A library for dates with no times or time zones
* [gtz](https://github.com/jrstrunk/gtz) ⭐ 4 | 🐛 0 | 🌐 Gleam | 📅 2026-08-01 - [📚](https://hexdocs.pm/gtz/) - A timezone data provider for Gleam!

### Validation

* [valid](https://github.com/sporto/gleam-validator) ⭐ 54 | 🐛 0 | 🌐 Gleam | 📅 2026-08-05 - [📚](https://hexdocs.pm/valid/) - A composable validation library for Gleam
* [crossbar](https://github.com/aosasona/crossbar) ⭐ 19 | 🐛 1 | 🌐 Gleam | 📅 2025-11-05 - [📚](https://hexdocs.pm/crossbar/) - Data validation library in pure Gleam

### Web frameworks

* [wisp](https://github.com/gleam-wisp/wisp) ⭐ 1,468 | 🐛 19 | 🌐 Gleam | 📅 2026-06-28 - [📚](https://hexdocs.pm/wisp/) - A practical web framework for Gleam
* [glimr](https://github.com/glimr-org/glimr) ⭐ 212 | 🐛 4 | 🌐 Gleam | 📅 2026-04-28 - [📚](https://hexdocs.pm/glimr/) - A batteries-included web framework for Gleam
* [glen](https://github.com/MystPi/glen) ⭐ 116 | 🐛 2 | 🌐 Gleam | 📅 2025-06-30 - [📚](https://hexdocs.pm/glen/) - A peaceful web framework that targets JS.

### Websites

* [lustre\_ssg](https://github.com/lustre-labs/ssg) ⭐ 107 | 🐛 4 | 🌐 Gleam | 📅 2026-01-05 - [📚](https://hexdocs.pm/lustre_ssg/) - A simple static site generator for Lustre projects.
* [blogatto](https://github.com/veeso/blogatto) ⭐ 96 | 🐛 2 | 🌐 Gleam | 📅 2026-07-29 - [📚](https://hexdocs.pm/blogatto/) - A framework for building static blogs with Lustre and Markdown
* [atomb](https://github.com/lpil/atomb) ⭐ 16 | 🐛 0 | 🌐 Gleam | 📅 2025-04-07 - [📚](https://hexdocs.pm/atomb/) - An Atom feed builder for Gleam

## Projects

### Compilers

Compilers for Gleam and compilers written in Gleam.

* [gleam-lang/gleam](https://github.com/gleam-lang/gleam) ⭐ 21,750 | 🐛 232 | 🌐 Rust | 📅 2026-08-19 - The Gleam compiler.
* [gleam-lang/example-lisp-interpreter](https://github.com/gleam-lang/example-lisp-interpreter/) ⭐ 50 | 🐛 0 | 🌐 Gleam | 📅 2025-03-27 - A toy Lisp interpreter in Gleam.

### Web applications

Web applications written in Gleam.

* [gleam-lang/example-todomvc](https://github.com/gleam-lang/example-todomvc) ⭐ 157 | 🐛 5 | 🌐 Gleam | 📅 2024-07-15 - A serverside implementation of TodoMVC written in Gleam!
* [gleam-lang/packages](https://github.com/gleam-lang/packages) ⭐ 118 | 🐛 6 | 🌐 Gleam | 📅 2026-07-22 - The Gleam package index website.
* [ghivert/gloogle](https://github.com/ghivert/gloogle) ⭐ 117 | 🐛 7 | 🌐 Gleam | 📅 2026-07-02 - A search engine for the Gleam ecosystem, built in Lustre + Wisp.
* [gleam-lang/example-echo-server](https://github.com/gleam-lang/example-echo-server) ⭐ 81 | 🐛 2 | 🌐 Gleam | 📅 2025-04-13 - An example Gleam web application.
* [aosasona/jsorm](https://github.com/aosasona/jsorm) ⭐ 32 | 🐛 15 | 🌐 Gleam | 📅 2026-07-28 - A minimal JSON explorer in Gleam + HTMX.
* [ryanmiville/lustre-todomvc](https://github.com/ryanmiville/lustre-todomvc) ⭐ 23 | 🐛 0 | 🌐 Gleam | 📅 2025-04-22 - A Lustre clientside implementation of TodoMVC written in Gleam!
* [losfair/acquire](https://github.com/losfair/acquire) ⭐ 10 | 🐛 0 | 🌐 Gleam | 📅 2025-03-23 - A multiplayer board game written in Gleam.

### Network applications

Network applications/servers written in Gleam

* [zwubs/betamine](https://github.com/zwubs/betamine) ⭐ 41 | 🐛 0 | 🌐 Gleam | 📅 2026-04-23 - A Minecraft server written in Gleam
* [raineycat/gftp](https://github.com/raineycat/gleam-ftp) ⭐ 10 | 🐛 0 | 🌐 Gleam | 📅 2025-09-15 - A Gleam FTP server, using Erlang/OTP

## Tools

* [jonasgruenwald/spectator](https://github.com/JonasGruenwald/spectator) ⭐ 98 | 🐛 4 | 🌐 Gleam | 📅 2026-04-21 - A BEAM runtime observer tool
* [tynanbe/rad](https://github.com/tynanbe/rad) ⭐ 72 | 🐛 1 | 🌐 Gleam | 📅 2024-06-14 - A flexible task runner companion for the Gleam build manager.
* [inoas/glychee](https://github.com/inoas/glychee) ⭐ 22 | 🐛 5 | 🌐 Gleam | 📅 2026-05-23 - A simple Gleam benchmark runner which wraps Benchee for the heavy lifting.

## Editor support

* [sbdchd/neoformat](https://github.com/sbdchd/neoformat) ⭐ 2,048 | 🐛 130 | 🌐 Vim Script | 📅 2026-04-13 - A Vim/Neovim plugin for formatting code with support for `gleam format`.
* [gleam-lang/vscode-gleam](https://github.com/gleam-lang/vscode-gleam) ⭐ 234 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-10 - Gleam support for VS Code.
* [gleam-lang/gleam.vim](https://github.com/gleam-lang/gleam.vim) ⚠️ Archived - Gleam support for Vim/Neovim.
* [gleam-lang/gleam-mode](https://github.com/gleam-lang/gleam-mode) ⭐ 120 | 🐛 6 | 🌐 Emacs Lisp | 📅 2026-06-04 - An emacs major mode for the Gleam programming language.
* [digitalcora/sublime-text-gleam](https://github.com/digitalcora/sublime-text-gleam) ⭐ 18 | 🐛 1 | 🌐 Gleam | 📅 2026-07-25 - Gleam support for Sublime Text.
* [itsgreggreg/language-gleam](https://github.com/itsgreggreg/language-gleam) ⚠️ Archived - Gleam language support in Atom.
* [DannyLettuce/gleam\_gedit](https://github.com/DannyLettuce/gleam_gedit) ⭐ 4 | 🐛 0 | 📅 2023-01-15 - Gleam syntax support for Gedit (and other GtkSourceView editors).
* [0riginaln0/lite-xl-gleam](https://github.com/0riginaln0/lite-xl-gleam) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-05-28 - Gleam theme and syntax highlighting for Lite XL.

## Resources

### Websites

Websites with Gleam related content.

* [gleam.run](https://gleam.run) - Gleam's website.
* [tour.gleam.run](https://tour.gleam.run) - Gleam's interactive tour and tutorial.
* [gleamweekly.com](https://gleamweekly.com/) - A weekly newsletter of handpicked articles and community news.
* [gloogle.run](https://gloogle.run) - A search engine for the Gleam ecosystem.

### Courses

* [Exercism's Gleam track](https://github.com/exercism/gleam/) ⭐ 119 | 🐛 28 | 🌐 Gleam | 📅 2026-08-15 - Crowd-sourced code mentorship. Practice having thoughtful conversations about code.
* [tanklesxl/gladvent](https://github.com/tanklesxl/gladvent) ⭐ 70 | 🐛 10 | 🌐 Gleam | 📅 2025-10-27 - An `Advent of Code` runner for Gleam, targeting Erlang.

### Talks

* [Introduction to Gleam](https://fosdem.org/2023/schedule/event/beam_gleam_intro/) - [Harry Bairstow](https://github.com/harryet)
* [Distributed music programming with Gleam, BEAM, and the Web Audio API](https://fosdem.org/2023/schedule/event/beam_distributed_music_programming_gleam/) - [Hayleigh Thompson](https://github.com/hayleigh-dot-dev)
* [I learned Gleam in a week. Here's how it went](https://www.youtube.com/watch?v=-8OIK4RIUsg) - [Theo Harris](https://github.com/Theosaurus-Rex)

### Social Media

#### Twitter

* [#gleamlang hashtag](https://twitter.com/search?q=%23gleamlang\&src=typed_query)
* [@gleamlang](https://twitter.com/gleamlang) - The official twitter account.
* [@louispilfold](https://twitter.com/louispilfold) - The creator of Gleam.

#### Reddit

* [r/gleamlang](https://reddit.com/r/gleamlang/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
