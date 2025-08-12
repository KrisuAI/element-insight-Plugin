# Rust Third-Party Licenses

This document lists all Rust crates and their licenses used by the `element-insight-binary` and `framework-export-binary` components of the Element Insight VS Code Extension.

## Crate List and Details

### addr2line (0.24.2) - Apache-2.0 OR MIT

- **Repository**: https://github.com/gimli-rs/addr2line
- **Description**: A cross-platform symbolication library written in Rust, using `gimli`
- **Used by**: element-insight-binary, framework-export-binary

---

### adler2 (2.0.1) - 0BSD OR Apache-2.0 OR MIT

- **Authors**: Jonas Schievink <jonasschievink@gmail.com>|oyvindln <oyvindln@users.noreply.github.com>
- **Repository**: https://github.com/oyvindln/adler2
- **Description**: A simple clean-room implementation of the Adler-32 checksum
- **Used by**: element-insight-binary, framework-export-binary

---

### ahash (0.8.12) - Apache-2.0 OR MIT

- **Authors**: Tom Kaitchuck <Tom.Kaitchuck@gmail.com>
- **Repository**: https://github.com/tkaitchuck/ahash
- **Description**: A non-cryptographic hash function using AES-NI for high performance
- **Used by**: element-insight-binary, framework-export-binary

---

### aho-corasick (1.1.3) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/aho-corasick
- **Description**: Fast multiple substring searching.
- **Used by**: element-insight-binary, framework-export-binary

---

### alloc-no-stdlib (2.0.4) - BSD-3-Clause

- **Authors**: Daniel Reiter Horn <danielrh@dropbox.com>
- **Repository**: https://github.com/dropbox/rust-alloc-no-stdlib
- **Description**: A dynamic allocator that may be used with or without the stdlib. This allows a package with nostd to allocate memory dynamically and be used either with a custom allocator, items on the stack, or by a package that wishes to simply use Box<>. It also provides options to use calloc or a mutable global variable for pre-zeroed memory
- **Used by**: element-insight-binary

---

### alloc-stdlib (0.2.2) - BSD-3-Clause

- **Authors**: Daniel Reiter Horn <danielrh@dropbox.com>
- **Repository**: https://github.com/dropbox/rust-alloc-no-stdlib
- **Description**: A dynamic allocator example that may be used with the stdlib
- **Used by**: element-insight-binary

---

### android-tzdata (0.1.1) - Apache-2.0 OR MIT

- **Authors**: RumovZ
- **Repository**: https://github.com/RumovZ/android-tzdata
- **Description**: Parser for the Android-specific tzdata file
- **Used by**: element-insight-binary, framework-export-binary

---

### android_system_properties (0.1.5) - Apache-2.0 OR MIT

- **Authors**: Nicolas Silva <nical@fastmail.com>
- **Repository**: https://github.com/nical/android_system_properties
- **Description**: Minimal Android system properties wrapper
- **Used by**: element-insight-binary, framework-export-binary

---

### anstream (0.6.19) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-cli/anstyle.git
- **Description**: A simple cross platform library for writing colored text to a terminal.
- **Used by**: element-insight-binary, framework-export-binary

---

### anstyle (1.0.11) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-cli/anstyle.git
- **Description**: ANSI text styling
- **Used by**: element-insight-binary, framework-export-binary

---

### anstyle-parse (0.2.7) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-cli/anstyle.git
- **Description**: Parse ANSI Style Escapes
- **Used by**: element-insight-binary, framework-export-binary

---

### anstyle-query (1.1.3) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-cli/anstyle.git
- **Description**: Look up colored console capabilities
- **Used by**: element-insight-binary, framework-export-binary

---

### anstyle-wincon (3.0.9) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-cli/anstyle.git
- **Description**: Styling legacy Windows terminals
- **Used by**: element-insight-binary, framework-export-binary

---

### anyhow (1.0.98) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/anyhow
- **Description**: Flexible concrete Error type built on std::error::Error
- **Used by**: element-insight-binary

---

### async-compression (0.4.25) - Apache-2.0 OR MIT

- **Authors**: Wim Looman <wim@nemo157.com>|Allen Bui <fairingrey@gmail.com>
- **Repository**: https://github.com/Nullus157/async-compression
- **Description**: Adaptors between compression crates and Rust's modern asynchronous IO types.
- **Used by**: element-insight-binary

---

### async-stream (0.3.6) - MIT

- **Authors**: Carl Lerche <me@carllerche.com>
- **Repository**: https://github.com/tokio-rs/async-stream
- **Description**: Asynchronous streams using async & await notation
- **Used by**: element-insight-binary, framework-export-binary

---

### async-stream-impl (0.3.6) - MIT

- **Authors**: Carl Lerche <me@carllerche.com>
- **Repository**: https://github.com/tokio-rs/async-stream
- **Description**: proc macros for async-stream crate
- **Used by**: element-insight-binary, framework-export-binary

---

### autocfg (1.5.0) - Apache-2.0 OR MIT

- **Authors**: Josh Stone <cuviper@gmail.com>
- **Repository**: https://github.com/cuviper/autocfg
- **Description**: Automatic cfg for Rust compiler features
- **Used by**: element-insight-binary, framework-export-binary

---

### backtrace (0.3.75) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers
- **Repository**: https://github.com/rust-lang/backtrace-rs
- **Description**: A library to acquire a stack trace (backtrace) at runtime in a Rust program.
- **Used by**: element-insight-binary, framework-export-binary

---

### base64 (0.21.7) - Apache-2.0 OR MIT

- **Authors**: Alice Maz <alice@alicemaz.com>|Marshall Pierce <marshall@mpierce.org>
- **Repository**: https://github.com/marshallpierce/rust-base64
- **Description**: encodes and decodes base64 as bytes or utf8
- **Used by**: element-insight-binary

---

### bitflags (1.3.2) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers
- **Repository**: https://github.com/bitflags/bitflags
- **Description**: A macro to generate structures which behave like bitflags.
- **Used by**: element-insight-binary

---

### bitflags (2.9.1) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers
- **Repository**: https://github.com/bitflags/bitflags
- **Description**: A macro to generate structures which behave like bitflags.
- **Used by**: element-insight-binary, framework-export-binary

---

### block-buffer (0.10.4) - Apache-2.0 OR MIT

- **Authors**: RustCrypto Developers
- **Repository**: https://github.com/RustCrypto/utils
- **Description**: Buffer type for block processing of data
- **Used by**: framework-export-binary

---

### brotli (8.0.1) - BSD-3-Clause AND MIT

- **Authors**: Daniel Reiter Horn <danielrh@dropbox.com>|The Brotli Authors
- **Repository**: https://github.com/dropbox/rust-brotli
- **Description**: A brotli compressor and decompressor that with an interface avoiding the rust stdlib. This makes it suitable for embedded devices and kernels. It is designed with a pluggable allocator so that the standard lib's allocator may be employed. The default build also includes a stdlib allocator and stream interface. Disable this with --features=no-stdlib. All included code is safe.
- **Used by**: element-insight-binary

---

### brotli-decompressor (5.0.0) - BSD-3-Clause OR MIT

- **Authors**: Daniel Reiter Horn <danielrh@dropbox.com>|The Brotli Authors
- **Repository**: https://github.com/dropbox/rust-brotli-decompressor
- **Description**: A brotli decompressor that with an interface avoiding the rust stdlib. This makes it suitable for embedded devices and kernels. It is designed with a pluggable allocator so that the standard lib's allocator may be employed. The default build also includes a stdlib allocator and stream interface. Disable this with --features=no-stdlib. Alternatively, --features=unsafe turns off array bounds checks and memory initialization but provides a safe interface for the caller.  Without adding the --features=unsafe argument, all included code is safe. For compression in addition to this library, download https://github.com/dropbox/rust-brotli
- **Used by**: element-insight-binary

---

### bstr (1.12.0) - Apache-2.0 OR MIT

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/bstr
- **Description**: A string type that is not required to be valid UTF-8.
- **Used by**: framework-export-binary

---

### bumpalo (3.19.0) - Apache-2.0 OR MIT

- **Authors**: Nick Fitzgerald <fitzgen@gmail.com>
- **Repository**: https://github.com/fitzgen/bumpalo
- **Description**: A fast bump allocation arena for Rust.
- **Used by**: element-insight-binary, framework-export-binary

---

### byteorder (1.5.0) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/byteorder
- **Description**: Library for reading/writing numbers in big-endian and little-endian.
- **Used by**: element-insight-binary, framework-export-binary

---

### bytes (1.10.1) - MIT

- **Authors**: Carl Lerche <me@carllerche.com>|Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/tokio-rs/bytes
- **Description**: Types and traits for working with bytes
- **Used by**: element-insight-binary, framework-export-binary

---

### cc (1.2.27) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>
- **Repository**: https://github.com/rust-lang/cc-rs
- **Description**: A build-time dependency for Cargo build scripts to assist in invoking the native C compiler to compile native C code into a static archive to be linked into Rust code.
- **Used by**: element-insight-binary, framework-export-binary

---

### cfg-if (1.0.1) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>
- **Repository**: https://github.com/rust-lang/cfg-if
- **Description**: A macro to ergonomically define an item depending on a large number of #[cfg] parameters. Structured like an if-else chain, the first matching branch is the item that gets emitted.
- **Used by**: element-insight-binary, framework-export-binary

---

### chrono (0.4.41) - Apache-2.0 OR MIT

- **Repository**: https://github.com/chronotope/chrono
- **Description**: Date and time library for Rust
- **Used by**: element-insight-binary, framework-export-binary

---

### chrono-tz (0.9.0) - Apache-2.0 OR MIT

- **Repository**: https://github.com/chronotope/chrono-tz
- **Description**: TimeZone implementations for chrono from the IANA database
- **Used by**: framework-export-binary

---

### chrono-tz-build (0.3.0) - Apache-2.0 OR MIT

- **Repository**: https://github.com/chronotope/chrono-tz
- **Description**: internal build script for chrono-tz
- **Used by**: framework-export-binary

---

### clap (4.5.40) - Apache-2.0 OR MIT

- **Repository**: https://github.com/clap-rs/clap
- **Description**: A simple to use, efficient, and full-featured Command Line Argument Parser
- **Used by**: element-insight-binary, framework-export-binary

---

### clap_builder (4.5.40) - Apache-2.0 OR MIT

- **Repository**: https://github.com/clap-rs/clap
- **Description**: A simple to use, efficient, and full-featured Command Line Argument Parser
- **Used by**: element-insight-binary, framework-export-binary

---

### clap_derive (4.5.40) - Apache-2.0 OR MIT

- **Repository**: https://github.com/clap-rs/clap
- **Description**: Parse command line argument by defining a struct, derive crate.
- **Used by**: element-insight-binary, framework-export-binary

---

### clap_lex (0.7.5) - Apache-2.0 OR MIT

- **Repository**: https://github.com/clap-rs/clap
- **Description**: Minimal, flexible command line parser
- **Used by**: element-insight-binary, framework-export-binary

---

### colorchoice (1.0.4) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-cli/anstyle.git
- **Description**: Global override of color control
- **Used by**: element-insight-binary, framework-export-binary

---

### convert_case (0.4.0) - MIT

- **Authors**: David Purdum <purdum41@gmail.com>
- **Repository**: https://github.com/rutrum/convert-case
- **Description**: Convert strings into any case
- **Used by**: element-insight-binary, framework-export-binary

---

### convert_case (0.6.0) - MIT

- **Authors**: Rutrum <dave@rutrum.net>
- **Repository**: https://github.com/rutrum/convert-case
- **Description**: Convert strings into any case
- **Used by**: element-insight-binary, framework-export-binary

---

### core-foundation (0.9.4) - Apache-2.0 OR MIT

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/core-foundation-rs
- **Description**: Bindings to Core Foundation for macOS
- **Used by**: element-insight-binary

---

### core-foundation-sys (0.8.7) - Apache-2.0 OR MIT

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/core-foundation-rs
- **Description**: Bindings to Core Foundation for macOS
- **Used by**: element-insight-binary, framework-export-binary

---

### cpufeatures (0.2.17) - Apache-2.0 OR MIT

- **Authors**: RustCrypto Developers
- **Repository**: https://github.com/RustCrypto/utils
- **Description**: Lightweight runtime CPU feature detection for aarch64, loongarch64, and x86/x86_64 targets,  with no_std support and support for mobile targets including Android and iOS
- **Used by**: framework-export-binary

---

### crc32fast (1.4.2) - Apache-2.0 OR MIT

- **Authors**: Sam Rijs <srijs@airpost.net>|Alex Crichton <alex@alexcrichton.com>
- **Repository**: https://github.com/srijs/rust-crc32fast
- **Description**: Fast, SIMD-accelerated CRC32 (IEEE) checksum computation
- **Used by**: element-insight-binary

---

### crossbeam-deque (0.8.6) - Apache-2.0 OR MIT

- **Repository**: https://github.com/crossbeam-rs/crossbeam
- **Description**: Concurrent work-stealing deque
- **Used by**: framework-export-binary

---

### crossbeam-epoch (0.9.18) - Apache-2.0 OR MIT

- **Repository**: https://github.com/crossbeam-rs/crossbeam
- **Description**: Epoch-based garbage collection
- **Used by**: framework-export-binary

---

### crossbeam-utils (0.8.21) - Apache-2.0 OR MIT

- **Repository**: https://github.com/crossbeam-rs/crossbeam
- **Description**: Utilities for concurrent programming
- **Used by**: framework-export-binary

---

### crypto-common (0.1.6) - Apache-2.0 OR MIT

- **Authors**: RustCrypto Developers
- **Repository**: https://github.com/RustCrypto/traits
- **Description**: Common cryptographic traits
- **Used by**: framework-export-binary

---

### cssparser (0.27.2) - MPL-2.0

- **Authors**: Simon Sapin <simon.sapin@exyr.org>
- **Repository**: https://github.com/servo/rust-cssparser
- **Description**: Rust implementation of CSS Syntax Level 3
- **Used by**: element-insight-binary

---

### cssparser (0.31.2) - MPL-2.0

- **Authors**: Simon Sapin <simon.sapin@exyr.org>
- **Repository**: https://github.com/servo/rust-cssparser
- **Description**: Rust implementation of CSS Syntax Level 3
- **Used by**: element-insight-binary, framework-export-binary

---

### cssparser (0.33.0) - MPL-2.0

- **Authors**: Simon Sapin <simon.sapin@exyr.org>
- **Repository**: https://github.com/servo/rust-cssparser
- **Description**: Rust implementation of CSS Syntax Level 3
- **Used by**: element-insight-binary

---

### cssparser-macros (0.6.1) - MPL-2.0

- **Authors**: Simon Sapin <simon.sapin@exyr.org>
- **Repository**: https://github.com/servo/rust-cssparser
- **Description**: Procedural macros for cssparser
- **Used by**: element-insight-binary, framework-export-binary

---

### csv (1.3.1) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/rust-csv
- **Description**: Fast CSV parsing with support for serde.
- **Used by**: element-insight-binary

---

### csv-core (0.1.12) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/rust-csv
- **Description**: Bare bones CSV parsing with no_std support.
- **Used by**: element-insight-binary

---

### derive_more (0.99.20) - MIT

- **Authors**: Jelte Fennema <github-tech@jeltef.nl>
- **Repository**: https://github.com/JelteF/derive_more
- **Description**: Adds #[derive(x)] macros for more traits
- **Used by**: element-insight-binary, framework-export-binary

---

### deunicode (1.6.2) - BSD-3-Clause

- **Authors**: Kornel Lesinski <kornel@geekhood.net>|Amit Chowdhury <amitc97@gmail.com>
- **Repository**: https://github.com/kornelski/deunicode/
- **Description**: Convert Unicode strings to pure ASCII by intelligently transliterating them. Suppors Emoji and Chinese.
- **Used by**: framework-export-binary

---

### digest (0.10.7) - Apache-2.0 OR MIT

- **Authors**: RustCrypto Developers
- **Repository**: https://github.com/RustCrypto/traits
- **Description**: Traits for cryptographic hash functions and message authentication codes
- **Used by**: framework-export-binary

---

### displaydoc (0.2.5) - Apache-2.0 OR MIT

- **Authors**: Jane Lusby <jlusby@yaah.dev>
- **Repository**: https://github.com/yaahc/displaydoc
- **Description**: A derive macro for implementing the display Trait via a doc comment and string interpolation
- **Used by**: element-insight-binary

---

### dtoa (1.0.10) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/dtoa
- **Description**: Fast floating point primitive to string conversion
- **Used by**: element-insight-binary, framework-export-binary

---

### dtoa-short (0.3.5) - MPL-2.0

- **Authors**: Xidorn Quan <me@upsuper.org>
- **Repository**: https://github.com/upsuper/dtoa-short
- **Description**: Serialize float number and truncate to certain precision
- **Used by**: element-insight-binary, framework-export-binary

---

### ego-tree (0.6.3) - ISC

- **Authors**: June McEnroe <june@causal.agency>|Carlo Federico Vescovo <vescovocarlofederico@gmail.com>
- **Repository**: https://github.com/rust-scraper/ego-tree
- **Description**: Vec-backed ID-tree
- **Used by**: element-insight-binary, framework-export-binary

---

### element-insight-binary (0.1.0) - MIT

- **Authors**: TestIn01 Team
- **Description**: Element Insight binary for TestIn01 VS Code extension
- **Used by**: element-insight-binary

---

### encoding_rs (0.8.35) - (Apache-2.0 OR MIT) AND BSD-3-Clause

- **Authors**: Henri Sivonen <hsivonen@hsivonen.fi>
- **Repository**: https://github.com/hsivonen/encoding_rs
- **Description**: A Gecko-oriented implementation of the Encoding Standard
- **Used by**: element-insight-binary

---

### equivalent (1.0.2) - Apache-2.0 OR MIT

- **Repository**: https://github.com/indexmap-rs/equivalent
- **Description**: Traits for key comparison in maps.
- **Used by**: element-insight-binary

---

### errno (0.3.13) - Apache-2.0 OR MIT

- **Authors**: Chris Wong <lambda.fairy@gmail.com>|Dan Gohman <dev@sunfishcode.online>
- **Repository**: https://github.com/lambda-fairy/rust-errno
- **Description**: Cross-platform interface to the `errno` variable.
- **Used by**: element-insight-binary, framework-export-binary

---

### fastrand (2.3.0) - Apache-2.0 OR MIT

- **Authors**: Stjepan Glavina <stjepang@gmail.com>
- **Repository**: https://github.com/smol-rs/fastrand
- **Description**: A simple and fast random number generator
- **Used by**: element-insight-binary, framework-export-binary

---

### flate2 (1.1.2) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>|Josh Triplett <josh@joshtriplett.org>
- **Repository**: https://github.com/rust-lang/flate2-rs
- **Description**: DEFLATE compression and decompression exposed as Read/BufRead/Write streams. Supports miniz_oxide and multiple zlib implementations. Supports zlib, gzip, and raw deflate streams.
- **Used by**: element-insight-binary

---

### fnv (1.0.7) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>
- **Repository**: https://github.com/servo/rust-fnv
- **Description**: FowlerΓÇôNollΓÇôVo hash function
- **Used by**: element-insight-binary

---

### foreign-types (0.3.2) - Apache-2.0 OR MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/foreign-types
- **Description**: A framework for Rust wrappers over C APIs
- **Used by**: element-insight-binary

---

### foreign-types-shared (0.1.1) - Apache-2.0 OR MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/foreign-types
- **Description**: An internal crate used by foreign-types
- **Used by**: element-insight-binary

---

### form_urlencoded (1.2.1) - Apache-2.0 OR MIT

- **Authors**: The rust-url developers
- **Repository**: https://github.com/servo/rust-url
- **Description**: Parser and serializer for the application/x-www-form-urlencoded syntax, as used by HTML forms.
- **Used by**: element-insight-binary

---

### framework-export-binary (0.1.0) - MIT

- **Authors**: TestIn01 Team
- **Description**: Framework Export binary for TestIn01 VS Code extension
- **Used by**: framework-export-binary

---

### futf (0.1.5) - Apache-2.0 OR MIT

- **Authors**: Keegan McAllister <kmcallister@mozilla.com>
- **Repository**: https://github.com/servo/futf
- **Description**: Handling fragments of UTF-8
- **Used by**: element-insight-binary, framework-export-binary

---

### futures-channel (0.3.31) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-lang/futures-rs
- **Description**: Channels for asynchronous communication using futures-rs.
- **Used by**: element-insight-binary

---

### futures-core (0.3.31) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-lang/futures-rs
- **Description**: The core traits and types in for the `futures` library.
- **Used by**: element-insight-binary, framework-export-binary

---

### futures-io (0.3.31) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-lang/futures-rs
- **Description**: The `AsyncRead`, `AsyncWrite`, `AsyncSeek`, and `AsyncBufRead` traits for the futures-rs library.
- **Used by**: element-insight-binary

---

### futures-macro (0.3.31) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-lang/futures-rs
- **Description**: The futures-rs procedural macro implementations.
- **Used by**: element-insight-binary

---

### futures-sink (0.3.31) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-lang/futures-rs
- **Description**: The asynchronous `Sink` trait for the futures-rs library.
- **Used by**: element-insight-binary

---

### futures-task (0.3.31) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-lang/futures-rs
- **Description**: Tools for working with tasks.
- **Used by**: element-insight-binary

---

### futures-util (0.3.31) - Apache-2.0 OR MIT

- **Repository**: https://github.com/rust-lang/futures-rs
- **Description**: Common utilities and extension traits for the futures-rs library.
- **Used by**: element-insight-binary

---

### fxhash (0.2.1) - Apache-2.0 OR MIT

- **Authors**: cbreeden <github@u.breeden.cc>
- **Repository**: https://github.com/cbreeden/fxhash
- **Description**: A fast, non-secure, hashing algorithm derived from an internal hasher used in FireFox and Rustc.
- **Used by**: element-insight-binary, framework-export-binary

---

### generic-array (0.14.7) - MIT

- **Authors**: Bart┼éomiej Kami┼äski <fizyk20@gmail.com>|Aaron Trent <novacrazy@gmail.com>
- **Repository**: https://github.com/fizyk20/generic-array.git
- **Description**: Generic types implementing functionality of arrays
- **Used by**: framework-export-binary

---

### getopts (0.2.23) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers
- **Repository**: https://github.com/rust-lang/getopts
- **Description**: getopts-like option parsing
- **Used by**: element-insight-binary, framework-export-binary

---

### getrandom (0.1.16) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers
- **Repository**: https://github.com/rust-random/getrandom
- **Description**: A small cross-platform library for retrieving random data from system source
- **Used by**: element-insight-binary

---

### getrandom (0.2.16) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers
- **Repository**: https://github.com/rust-random/getrandom
- **Description**: A small cross-platform library for retrieving random data from system source
- **Used by**: element-insight-binary, framework-export-binary

---

### getrandom (0.3.3) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers
- **Repository**: https://github.com/rust-random/getrandom
- **Description**: A small cross-platform library for retrieving random data from system source
- **Used by**: element-insight-binary, framework-export-binary

---

### gimli (0.31.1) - Apache-2.0 OR MIT

- **Repository**: https://github.com/gimli-rs/gimli
- **Description**: A library for reading and writing the DWARF debugging format.
- **Used by**: element-insight-binary, framework-export-binary

---

### globset (0.4.16) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/ripgrep/tree/master/crates/globset
- **Description**: Cross platform single glob and glob set matching. Glob set matching is the process of matching one or more glob patterns against a single candidate path simultaneously, and returning all of the globs that matched.
- **Used by**: framework-export-binary

---

### globwalk (0.9.1) - MIT

- **Authors**: Gilad Naaman <gilad@naaman.io>
- **Repository**: https://github.com/gilnaa/globwalk
- **Description**: Glob-matched recursive file system walking.
- **Used by**: framework-export-binary

---

### h2 (0.3.26) - MIT

- **Authors**: Carl Lerche <me@carllerche.com>|Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/hyperium/h2
- **Description**: An HTTP/2 client and server
- **Used by**: element-insight-binary

---

### hashbrown (0.15.4) - Apache-2.0 OR MIT

- **Authors**: Amanieu d'Antras <amanieu@gmail.com>
- **Repository**: https://github.com/rust-lang/hashbrown
- **Description**: A Rust port of Google's SwissTable hash map
- **Used by**: element-insight-binary

---

### heck (0.4.1) - Apache-2.0 OR MIT

- **Authors**: Without Boats <woboats@gmail.com>
- **Repository**: https://github.com/withoutboats/heck
- **Description**: heck is a case conversion library.
- **Used by**: element-insight-binary, framework-export-binary

---

### heck (0.5.0) - Apache-2.0 OR MIT

- **Repository**: https://github.com/withoutboats/heck
- **Description**: heck is a case conversion library.
- **Used by**: element-insight-binary, framework-export-binary

---

### html-escape (0.2.13) - MIT

- **Authors**: Magic Len <len@magiclen.org>
- **Repository**: https://github.com/magiclen/html-escape
- **Description**: This library is for encoding/escaping special characters in HTML and decoding/unescaping HTML entities as well.
- **Used by**: element-insight-binary, framework-export-binary

---

### html5ever (0.25.2) - Apache-2.0 OR MIT

- **Authors**: The html5ever Project Developers
- **Repository**: https://github.com/servo/html5ever
- **Description**: High-performance browser-grade HTML5 parser
- **Used by**: element-insight-binary

---

### html5ever (0.26.0) - Apache-2.0 OR MIT

- **Authors**: The html5ever Project Developers
- **Repository**: https://github.com/servo/html5ever
- **Description**: High-performance browser-grade HTML5 parser
- **Used by**: element-insight-binary, framework-export-binary

---

### http (0.2.12) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>|Carl Lerche <me@carllerche.com>|Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/hyperium/http
- **Description**: A set of types for representing HTTP requests and responses.
- **Used by**: element-insight-binary

---

### http-body (0.4.6) - MIT

- **Authors**: Carl Lerche <me@carllerche.com>|Lucio Franco <luciofranco14@gmail.com>|Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/hyperium/http-body
- **Description**: Trait representing an asynchronous, streaming, HTTP request or response body.
- **Used by**: element-insight-binary

---

### httparse (1.10.1) - Apache-2.0 OR MIT

- **Authors**: Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/seanmonstar/httparse
- **Description**: A tiny, safe, speedy, zero-copy HTTP/1.x parser.
- **Used by**: element-insight-binary

---

### httpdate (1.0.3) - Apache-2.0 OR MIT

- **Authors**: Pyfisch <pyfisch@posteo.org>
- **Repository**: https://github.com/pyfisch/httpdate
- **Description**: HTTP date parsing and formatting
- **Used by**: element-insight-binary

---

### humansize (2.1.3) - Apache-2.0 OR MIT

- **Authors**: Leopold Arkham <leopold.arkham@gmail.com>
- **Repository**: https://github.com/LeopoldArkham/humansize
- **Description**: A configurable crate to easily represent sizes in a human-readable format.
- **Used by**: framework-export-binary

---

### hyper (0.14.32) - MIT

- **Authors**: Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/hyperium/hyper
- **Description**: A fast and correct HTTP library.
- **Used by**: element-insight-binary

---

### hyper-tls (0.5.0) - Apache-2.0 OR MIT

- **Authors**: Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/hyperium/hyper-tls
- **Description**: Default TLS implementation for use with hyper
- **Used by**: element-insight-binary

---

### iana-time-zone (0.1.63) - Apache-2.0 OR MIT

- **Authors**: Andrew Straw <strawman@astraw.com>|Ren├⌐ Kijewski <rene.kijewski@fu-berlin.de>|Ryan Lopopolo <rjl@hyperbo.la>
- **Repository**: https://github.com/strawlab/iana-time-zone
- **Description**: get the IANA time zone for the current system
- **Used by**: element-insight-binary, framework-export-binary

---

### iana-time-zone-haiku (0.1.2) - Apache-2.0 OR MIT

- **Authors**: Ren├⌐ Kijewski <crates.io@k6i.de>
- **Repository**: https://github.com/strawlab/iana-time-zone
- **Description**: iana-time-zone support crate for Haiku OS
- **Used by**: element-insight-binary, framework-export-binary

---

### icu_collections (2.0.0) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Collection of API for use in ICU libraries.
- **Used by**: element-insight-binary

---

### icu_locale_core (2.0.0) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: API for managing Unicode Language and Locale Identifiers
- **Used by**: element-insight-binary

---

### icu_normalizer (2.0.0) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: API for normalizing text into Unicode Normalization Forms
- **Used by**: element-insight-binary

---

### icu_normalizer_data (2.0.0) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Data for the icu_normalizer crate
- **Used by**: element-insight-binary

---

### icu_properties (2.0.1) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Definitions for Unicode properties
- **Used by**: element-insight-binary

---

### icu_properties_data (2.0.1) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Data for the icu_properties crate
- **Used by**: element-insight-binary

---

### icu_provider (2.0.0) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Trait and struct definitions for the ICU data provider
- **Used by**: element-insight-binary

---

### idna (1.0.3) - Apache-2.0 OR MIT

- **Authors**: The rust-url developers
- **Repository**: https://github.com/servo/rust-url/
- **Description**: IDNA (Internationalizing Domain Names in Applications) and Punycode.
- **Used by**: element-insight-binary

---

### idna_adapter (1.2.1) - Apache-2.0 OR MIT

- **Authors**: The rust-url developers
- **Repository**: https://github.com/hsivonen/idna_adapter
- **Description**: Back end adapter for idna
- **Used by**: element-insight-binary

---

### ignore (0.4.23) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/ripgrep/tree/master/crates/ignore
- **Description**: A fast library for efficiently matching ignore files such as `.gitignore` against file paths.
- **Used by**: framework-export-binary

---

### indexmap (2.10.0) - Apache-2.0 OR MIT

- **Repository**: https://github.com/indexmap-rs/indexmap
- **Description**: A hash table with consistent order and fast iteration.
- **Used by**: element-insight-binary

---

### ipnet (2.11.0) - Apache-2.0 OR MIT

- **Authors**: Kris Price <kris@krisprice.nz>
- **Repository**: https://github.com/krisprice/ipnet
- **Description**: Provides types and useful methods for working with IPv4 and IPv6 network addresses, commonly called IP prefixes. The new `IpNet`, `Ipv4Net`, and `Ipv6Net` types build on the existing `IpAddr`, `Ipv4Addr`, and `Ipv6Addr` types already provided in Rust's standard library and align to their design to stay consistent. The module also provides useful traits that extend `Ipv4Addr` and `Ipv6Addr` with methods for `Add`, `Sub`, `BitAnd`, and `BitOr` operations. The module only uses stable feature so it is guaranteed to compile using the stable toolchain.
- **Used by**: element-insight-binary

---

### is_terminal_polyfill (1.70.1) - Apache-2.0 OR MIT

- **Repository**: https://github.com/polyfill-rs/is_terminal_polyfill
- **Description**: Polyfill for `is_terminal` stdlib feature for use with older MSRVs
- **Used by**: element-insight-binary, framework-export-binary

---

### itoa (0.4.8) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/itoa
- **Description**: Fast functions for printing integer primitives to an io::Write
- **Used by**: element-insight-binary

---

### itoa (1.0.15) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/itoa
- **Description**: Fast integer primitive to string conversion
- **Used by**: element-insight-binary, framework-export-binary

---

### js-sys (0.3.77) - Apache-2.0 OR MIT

- **Authors**: The wasm-bindgen Developers
- **Repository**: https://github.com/rustwasm/wasm-bindgen/tree/master/crates/js-sys
- **Description**: Bindings for all JS global objects and functions in all JS environments like Node.js and browsers, built on `#[wasm_bindgen]` using the `wasm-bindgen` crate.
- **Used by**: element-insight-binary, framework-export-binary

---

### kuchiki (0.8.1) - MIT

- **Authors**: Simon Sapin <simon.sapin@exyr.org>
- **Repository**: https://github.com/SimonSapin/kuchiki
- **Description**: (µ£╜µ£¿) HTML/XML tree manipulation library
- **Used by**: element-insight-binary

---

### lazy_static (1.5.0) - Apache-2.0 OR MIT

- **Authors**: Marvin L├╢bel <loebel.marvin@gmail.com>
- **Repository**: https://github.com/rust-lang-nursery/lazy-static.rs
- **Description**: A macro for declaring lazily evaluated statics in Rust.
- **Used by**: element-insight-binary, framework-export-binary

---

### libc (0.2.174) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers
- **Repository**: https://github.com/rust-lang/libc
- **Description**: Raw FFI bindings to platform libraries like libc.
- **Used by**: element-insight-binary, framework-export-binary

---

### libm (0.2.15) - MIT

- **Authors**: Jorge Aparicio <jorge@japaric.io>
- **Repository**: https://github.com/rust-lang/compiler-builtins
- **Description**: libm in pure Rust
- **Used by**: framework-export-binary

---

### linux-raw-sys (0.9.4) - Apache-2.0 OR Apache-2.0 WITH LLVM-exception OR MIT

- **Authors**: Dan Gohman <dev@sunfishcode.online>
- **Repository**: https://github.com/sunfishcode/linux-raw-sys
- **Description**: Generated bindings for Linux's userspace API
- **Used by**: element-insight-binary, framework-export-binary

---

### litemap (0.8.0) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: A key-value Map implementation based on a flat, sorted Vec.
- **Used by**: element-insight-binary

---

### lock_api (0.4.13) - Apache-2.0 OR MIT

- **Authors**: Amanieu d'Antras <amanieu@gmail.com>
- **Repository**: https://github.com/Amanieu/parking_lot
- **Description**: Wrappers to create fully-featured Mutex and RwLock types. Compatible with no_std.
- **Used by**: element-insight-binary, framework-export-binary

---

### log (0.4.27) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers
- **Repository**: https://github.com/rust-lang/log
- **Description**: A lightweight logging facade for Rust
- **Used by**: element-insight-binary, framework-export-binary

---

### mac (0.1.1) - Apache-2.0 OR MIT

- **Authors**: Jonathan Reem <jonathan.reem@gmail.com>
- **Repository**: https://github.com/reem/rust-mac.git
- **Description**: A collection of great and ubiqutitous macros.
- **Used by**: element-insight-binary, framework-export-binary

---

### markup5ever (0.10.1) - Apache-2.0 OR MIT

- **Authors**: The html5ever Project Developers
- **Repository**: https://github.com/servo/html5ever
- **Description**: Common code for xml5ever and html5ever
- **Used by**: element-insight-binary

---

### markup5ever (0.11.0) - Apache-2.0 OR MIT

- **Authors**: The html5ever Project Developers
- **Repository**: https://github.com/servo/html5ever
- **Description**: Common code for xml5ever and html5ever
- **Used by**: element-insight-binary, framework-export-binary

---

### markup5ever_rcdom (0.2.0) - Apache-2.0 OR MIT

- **Authors**: The html5ever Project Developers
- **Repository**: https://github.com/servo/html5ever
- **Description**: Basic, unsupported DOM structure for use by tests in html5ever/xml5ever
- **Used by**: element-insight-binary

---

### matchers (0.1.0) - MIT

- **Authors**: Eliza Weisman <eliza@buoyant.io>
- **Repository**: https://github.com/hawkw/matchers
- **Description**: Regex matching on character and byte streams.
- **Used by**: element-insight-binary, framework-export-binary

---

### matches (0.1.10) - MIT

- **Repository**: https://github.com/SimonSapin/rust-std-candidates
- **Description**: A macro to evaluate, as a boolean, whether an expression matches a pattern.
- **Used by**: element-insight-binary

---

### memchr (2.7.5) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>|bluss
- **Repository**: https://github.com/BurntSushi/memchr
- **Description**: Provides extremely fast (uses SIMD on x86_64, aarch64 and wasm32) routines for 1, 2 or 3 byte search and single substring search.
- **Used by**: element-insight-binary, framework-export-binary

---

### mime (0.3.17) - Apache-2.0 OR MIT

- **Authors**: Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/hyperium/mime
- **Description**: Strongly Typed Mimes
- **Used by**: element-insight-binary

---

### miniz_oxide (0.8.9) - Apache-2.0 OR MIT OR Zlib

- **Authors**: Frommi <daniil.liferenko@gmail.com>|oyvindln <oyvindln@users.noreply.github.com>|Rich Geldreich richgel99@gmail.com
- **Repository**: https://github.com/Frommi/miniz_oxide/tree/master/miniz_oxide
- **Description**: DEFLATE compression and decompression library rewritten in Rust based on miniz
- **Used by**: element-insight-binary, framework-export-binary

---

### mio (1.0.4) - MIT

- **Authors**: Carl Lerche <me@carllerche.com>|Thomas de Zeeuw <thomasdezeeuw@gmail.com>|Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/mio
- **Description**: Lightweight non-blocking I/O.
- **Used by**: element-insight-binary, framework-export-binary

---

### native-tls (0.2.14) - Apache-2.0 OR MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-native-tls
- **Description**: A wrapper over a platform's native TLS implementation
- **Used by**: element-insight-binary

---

### new_debug_unreachable (1.0.6) - MIT

- **Authors**: Matt Brubeck <mbrubeck@limpet.net>|Jonathan Reem <jonathan.reem@gmail.com>
- **Repository**: https://github.com/mbrubeck/rust-debug-unreachable
- **Description**: panic in debug, intrinsics::unreachable() in release (fork of debug_unreachable)
- **Used by**: element-insight-binary, framework-export-binary

---

### nodrop (0.1.14) - Apache-2.0 OR MIT

- **Authors**: bluss
- **Repository**: https://github.com/bluss/arrayvec
- **Description**: A wrapper type to inhibit drop (destructor).  ***Deprecated: Use ManuallyDrop or MaybeUninit instead!***
- **Used by**: element-insight-binary

---

### nu-ansi-term (0.46.0) - MIT

- **Authors**: ogham@bsago.me|Ryan Scheel (Havvy) <ryan.havvy@gmail.com>|Josh Triplett <josh@joshtriplett.org>|The Nushell Project Developers
- **Repository**: https://github.com/nushell/nu-ansi-term
- **Description**: Library for ANSI terminal colors and styles (bold, underline)
- **Used by**: element-insight-binary, framework-export-binary

---

### num-traits (0.2.19) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers
- **Repository**: https://github.com/rust-num/num-traits
- **Description**: Numeric traits for generic mathematics
- **Used by**: element-insight-binary, framework-export-binary

---

### object (0.36.7) - Apache-2.0 OR MIT

- **Repository**: https://github.com/gimli-rs/object
- **Description**: A unified interface for reading and writing object file formats.
- **Used by**: element-insight-binary, framework-export-binary

---

### once_cell (1.21.3) - Apache-2.0 OR MIT

- **Authors**: Aleksey Kladov <aleksey.kladov@gmail.com>
- **Repository**: https://github.com/matklad/once_cell
- **Description**: Single assignment cells and lazy values.
- **Used by**: element-insight-binary, framework-export-binary

---

### once_cell_polyfill (1.70.1) - Apache-2.0 OR MIT

- **Repository**: https://github.com/polyfill-rs/once_cell_polyfill
- **Description**: Polyfill for `OnceCell` stdlib feature for use with older MSRVs
- **Used by**: element-insight-binary, framework-export-binary

---

### openssl (0.10.73) - Apache-2.0

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-openssl
- **Description**: OpenSSL bindings
- **Used by**: element-insight-binary

---

### openssl-macros (0.1.1) - Apache-2.0 OR MIT

- **Description**: Internal macros used by the openssl crate.
- **Used by**: element-insight-binary

---

### openssl-probe (0.1.6) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>
- **Repository**: https://github.com/alexcrichton/openssl-probe
- **Description**: Tool for helping to find SSL certificate locations on the system for OpenSSL
- **Used by**: element-insight-binary

---

### openssl-sys (0.9.109) - MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>|Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-openssl
- **Description**: FFI bindings to OpenSSL
- **Used by**: element-insight-binary

---

### overload (0.1.1) - MIT

- **Authors**: Daniel Salvadori <danaugrs@gmail.com>
- **Repository**: https://github.com/danaugrs/overload
- **Description**: Provides a macro to simplify operator overloading.
- **Used by**: element-insight-binary, framework-export-binary

---

### parking_lot (0.12.4) - Apache-2.0 OR MIT

- **Authors**: Amanieu d'Antras <amanieu@gmail.com>
- **Repository**: https://github.com/Amanieu/parking_lot
- **Description**: More compact and efficient implementations of the standard synchronization primitives.
- **Used by**: element-insight-binary, framework-export-binary

---

### parking_lot_core (0.9.11) - Apache-2.0 OR MIT

- **Authors**: Amanieu d'Antras <amanieu@gmail.com>
- **Repository**: https://github.com/Amanieu/parking_lot
- **Description**: An advanced API for creating custom synchronization primitives.
- **Used by**: element-insight-binary, framework-export-binary

---

### parse-zoneinfo (0.3.1) - MIT

- **Repository**: https://github.com/chronotope/chrono-tz
- **Description**: Parse zoneinfo files from the IANA database
- **Used by**: framework-export-binary

---

### percent-encoding (2.3.1) - Apache-2.0 OR MIT

- **Authors**: The rust-url developers
- **Repository**: https://github.com/servo/rust-url/
- **Description**: Percent encoding and decoding
- **Used by**: element-insight-binary, framework-export-binary

---

### peresil (0.3.0) - MIT

- **Authors**: Jake Goulding <jake.goulding@gmail.com>
- **Repository**: https://github.com/shepmaster/peresil
- **Description**: A simple and simplistic string parsing library
- **Used by**: element-insight-binary

---

### pest (2.8.1) - Apache-2.0 OR MIT

- **Authors**: Drago╚Ö Tiselice <dragostiselice@gmail.com>
- **Repository**: https://github.com/pest-parser/pest
- **Description**: The Elegant Parser
- **Used by**: framework-export-binary

---

### pest_derive (2.8.1) - Apache-2.0 OR MIT

- **Authors**: Drago╚Ö Tiselice <dragostiselice@gmail.com>
- **Repository**: https://github.com/pest-parser/pest
- **Description**: pest's derive macro
- **Used by**: framework-export-binary

---

### pest_generator (2.8.1) - Apache-2.0 OR MIT

- **Authors**: Drago╚Ö Tiselice <dragostiselice@gmail.com>
- **Repository**: https://github.com/pest-parser/pest
- **Description**: pest code generator
- **Used by**: framework-export-binary

---

### pest_meta (2.8.1) - Apache-2.0 OR MIT

- **Authors**: Drago╚Ö Tiselice <dragostiselice@gmail.com>
- **Repository**: https://github.com/pest-parser/pest
- **Description**: pest meta language parser and validator
- **Used by**: framework-export-binary

---

### phf (0.8.0) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: Runtime support for perfect hash function data structures
- **Used by**: element-insight-binary

---

### phf (0.10.1) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: Runtime support for perfect hash function data structures
- **Used by**: element-insight-binary, framework-export-binary

---

### phf (0.11.3) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/rust-phf/rust-phf
- **Description**: Runtime support for perfect hash function data structures
- **Used by**: element-insight-binary, framework-export-binary

---

### phf_codegen (0.8.0) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: Codegen library for PHF types
- **Used by**: element-insight-binary

---

### phf_codegen (0.10.0) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: Codegen library for PHF types
- **Used by**: element-insight-binary, framework-export-binary

---

### phf_codegen (0.11.3) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/rust-phf/rust-phf
- **Description**: Codegen library for PHF types
- **Used by**: framework-export-binary

---

### phf_generator (0.8.0) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: PHF generation logic
- **Used by**: element-insight-binary

---

### phf_generator (0.10.0) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: PHF generation logic
- **Used by**: element-insight-binary, framework-export-binary

---

### phf_generator (0.11.3) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/rust-phf/rust-phf
- **Description**: PHF generation logic
- **Used by**: element-insight-binary, framework-export-binary

---

### phf_macros (0.8.0) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: Macros to generate types in the phf crate
- **Used by**: element-insight-binary

---

### phf_macros (0.11.3) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/rust-phf/rust-phf
- **Description**: Macros to generate types in the phf crate
- **Used by**: element-insight-binary, framework-export-binary

---

### phf_shared (0.8.0) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: Support code shared by PHF libraries
- **Used by**: element-insight-binary

---

### phf_shared (0.10.0) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/sfackler/rust-phf
- **Description**: Support code shared by PHF libraries
- **Used by**: element-insight-binary, framework-export-binary

---

### phf_shared (0.11.3) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>
- **Repository**: https://github.com/rust-phf/rust-phf
- **Description**: Support code shared by PHF libraries
- **Used by**: element-insight-binary, framework-export-binary

---

### pin-project-lite (0.2.16) - Apache-2.0 OR MIT

- **Repository**: https://github.com/taiki-e/pin-project-lite
- **Description**: A lightweight version of pin-project written with declarative macros.
- **Used by**: element-insight-binary, framework-export-binary

---

### pin-utils (0.1.0) - Apache-2.0 OR MIT

- **Authors**: Josef Brandl <mail@josefbrandl.de>
- **Repository**: https://github.com/rust-lang-nursery/pin-utils
- **Description**: Utilities for pinning
- **Used by**: element-insight-binary

---

### pkg-config (0.3.32) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>
- **Repository**: https://github.com/rust-lang/pkg-config-rs
- **Description**: A library to run the pkg-config system tool at build time in order to be used in Cargo build scripts.
- **Used by**: element-insight-binary

---

### potential_utf (0.1.2) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Unvalidated string and character types
- **Used by**: element-insight-binary

---

### ppv-lite86 (0.2.21) - Apache-2.0 OR MIT

- **Authors**: The CryptoCorrosion Contributors
- **Repository**: https://github.com/cryptocorrosion/cryptocorrosion
- **Description**: Cross-platform cryptography-oriented low-level SIMD library.
- **Used by**: element-insight-binary, framework-export-binary

---

### precomputed-hash (0.1.1) - MIT

- **Authors**: Emilio Cobos ├ülvarez <emilio@crisal.io>
- **Repository**: https://github.com/emilio/precomputed-hash
- **Description**: A library intending to be a base dependency to expose a precomputed hash
- **Used by**: element-insight-binary, framework-export-binary

---

### proc-macro-hack (0.5.20+deprecated) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/proc-macro-hack
- **Description**: Procedural macros in expression position
- **Used by**: element-insight-binary

---

### proc-macro2 (1.0.95) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>|Alex Crichton <alex@alexcrichton.com>
- **Repository**: https://github.com/dtolnay/proc-macro2
- **Description**: A substitute implementation of the compiler's `proc_macro` API to decouple token-based libraries from the procedural macro use case.
- **Used by**: element-insight-binary, framework-export-binary

---

### quote (1.0.40) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/quote
- **Description**: Quasi-quoting macro quote!(...)
- **Used by**: element-insight-binary, framework-export-binary

---

### r-efi (5.3.0) - Apache-2.0 OR LGPL-2.1-or-later OR MIT

- **Repository**: https://github.com/r-efi/r-efi
- **Description**: UEFI Reference Specification Protocol Constants and Definitions
- **Used by**: element-insight-binary, framework-export-binary

---

### rand (0.7.3) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers|The Rust Project Developers
- **Repository**: https://github.com/rust-random/rand
- **Description**: Random number generators and other randomness functionality.
- **Used by**: element-insight-binary

---

### rand (0.8.5) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers|The Rust Project Developers
- **Repository**: https://github.com/rust-random/rand
- **Description**: Random number generators and other randomness functionality.
- **Used by**: element-insight-binary, framework-export-binary

---

### rand_chacha (0.2.2) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers|The Rust Project Developers|The CryptoCorrosion Contributors
- **Repository**: https://github.com/rust-random/rand
- **Description**: ChaCha random number generator
- **Used by**: element-insight-binary

---

### rand_chacha (0.3.1) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers|The Rust Project Developers|The CryptoCorrosion Contributors
- **Repository**: https://github.com/rust-random/rand
- **Description**: ChaCha random number generator
- **Used by**: element-insight-binary, framework-export-binary

---

### rand_core (0.5.1) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers|The Rust Project Developers
- **Repository**: https://github.com/rust-random/rand
- **Description**: Core random number generator traits and tools for implementation.
- **Used by**: element-insight-binary

---

### rand_core (0.6.4) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers|The Rust Project Developers
- **Repository**: https://github.com/rust-random/rand
- **Description**: Core random number generator traits and tools for implementation.
- **Used by**: element-insight-binary, framework-export-binary

---

### rand_hc (0.2.0) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers
- **Repository**: https://github.com/rust-random/rand
- **Description**: HC128 random number generator
- **Used by**: element-insight-binary

---

### rand_pcg (0.2.1) - Apache-2.0 OR MIT

- **Authors**: The Rand Project Developers
- **Repository**: https://github.com/rust-random/rand
- **Description**: Selected PCG random number generators
- **Used by**: element-insight-binary

---

### redox_syscall (0.5.13) - MIT

- **Authors**: Jeremy Soller <jackpot51@gmail.com>
- **Repository**: https://gitlab.redox-os.org/redox-os/syscall
- **Description**: A Rust library to access raw Redox system calls
- **Used by**: element-insight-binary, framework-export-binary

---

### regex (1.11.1) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers|Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/rust-lang/regex
- **Description**: An implementation of regular expressions for Rust. This implementation uses finite automata and guarantees linear time matching on all inputs.
- **Used by**: element-insight-binary, framework-export-binary

---

### regex-automata (0.1.10) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/regex-automata
- **Description**: Automata construction and matching using regular expressions.
- **Used by**: element-insight-binary, framework-export-binary

---

### regex-automata (0.4.9) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers|Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/rust-lang/regex/tree/master/regex-automata
- **Description**: Automata construction and matching using regular expressions.
- **Used by**: element-insight-binary, framework-export-binary

---

### regex-syntax (0.6.29) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers
- **Repository**: https://github.com/rust-lang/regex
- **Description**: A regular expression parser.
- **Used by**: element-insight-binary, framework-export-binary

---

### regex-syntax (0.8.5) - Apache-2.0 OR MIT

- **Authors**: The Rust Project Developers|Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/rust-lang/regex/tree/master/regex-syntax
- **Description**: A regular expression parser.
- **Used by**: element-insight-binary, framework-export-binary

---

### reqwest (0.11.27) - Apache-2.0 OR MIT

- **Authors**: Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/seanmonstar/reqwest
- **Description**: higher level HTTP client library
- **Used by**: element-insight-binary

---

### rustc-demangle (0.1.25) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>
- **Repository**: https://github.com/rust-lang/rustc-demangle
- **Description**: Rust compiler symbol demangling.
- **Used by**: element-insight-binary, framework-export-binary

---

### rustc_version (0.4.1) - Apache-2.0 OR MIT

- **Repository**: https://github.com/djc/rustc-version-rs
- **Description**: A library for querying the version of a installed rustc compiler
- **Used by**: element-insight-binary, framework-export-binary

---

### rustix (1.0.7) - Apache-2.0 OR Apache-2.0 WITH LLVM-exception OR MIT

- **Authors**: Dan Gohman <dev@sunfishcode.online>|Jakub Konka <kubkon@jakubkonka.com>
- **Repository**: https://github.com/bytecodealliance/rustix
- **Description**: Safe Rust bindings to POSIX/Unix/Linux/Winsock-like syscalls
- **Used by**: element-insight-binary, framework-export-binary

---

### rustls-pemfile (1.0.4) - Apache-2.0 OR ISC OR MIT

- **Repository**: https://github.com/rustls/pemfile
- **Description**: Basic .pem file parser for keys and certificates
- **Used by**: element-insight-binary

---

### rustversion (1.0.21) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/rustversion
- **Description**: Conditional compilation according to rustc compiler version
- **Used by**: element-insight-binary, framework-export-binary

---

### ryu (1.0.20) - Apache-2.0 OR BSL-1.0

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/ryu
- **Description**: Fast floating point to string conversion
- **Used by**: element-insight-binary, framework-export-binary

---

### same-file (1.0.6) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/same-file
- **Description**: A simple crate for determining whether two file paths point to the same file.
- **Used by**: framework-export-binary

---

### schannel (0.1.27) - MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>|Steffen Butzer <steffen.butzer@outlook.com>
- **Repository**: https://github.com/steffengy/schannel-rs
- **Description**: Schannel bindings for rust, allowing SSL/TLS (e.g. https) without openssl
- **Used by**: element-insight-binary

---

### scopeguard (1.2.0) - Apache-2.0 OR MIT

- **Authors**: bluss
- **Repository**: https://github.com/bluss/scopeguard
- **Description**: A RAII scope guard that will run a given closure when it goes out of scope, even if the code between panics (assuming unwinding panic).  Defines the macros `defer!`, `defer_on_unwind!`, `defer_on_success!` as shorthands for guards with one of the implemented strategies.
- **Used by**: element-insight-binary, framework-export-binary

---

### scraper (0.18.1) - ISC

- **Authors**: June McEnroe <june@causal.agency>
- **Repository**: https://github.com/causal-agent/scraper
- **Description**: HTML parsing and querying with CSS selectors
- **Used by**: element-insight-binary, framework-export-binary

---

### security-framework (2.11.1) - Apache-2.0 OR MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>|Kornel <kornel@geekhood.net>
- **Repository**: https://github.com/kornelski/rust-security-framework
- **Description**: Security.framework bindings for macOS and iOS
- **Used by**: element-insight-binary

---

### security-framework-sys (2.14.0) - Apache-2.0 OR MIT

- **Authors**: Steven Fackler <sfackler@gmail.com>|Kornel <kornel@geekhood.net>
- **Repository**: https://github.com/kornelski/rust-security-framework
- **Description**: Apple `Security.framework` low-level FFI bindings
- **Used by**: element-insight-binary

---

### selectors (0.22.0) - MPL-2.0

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/servo
- **Description**: CSS Selectors matching for Rust
- **Used by**: element-insight-binary

---

### selectors (0.25.0) - MPL-2.0

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/servo
- **Description**: CSS Selectors matching for Rust
- **Used by**: element-insight-binary, framework-export-binary

---

### semver (1.0.26) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/semver
- **Description**: Parser and evaluator for Cargo's flavor of Semantic Versioning
- **Used by**: element-insight-binary, framework-export-binary

---

### serde (1.0.219) - Apache-2.0 OR MIT

- **Authors**: Erick Tryzelaar <erick.tryzelaar@gmail.com>|David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/serde-rs/serde
- **Description**: A generic serialization/deserialization framework
- **Used by**: element-insight-binary, framework-export-binary

---

### serde_derive (1.0.219) - Apache-2.0 OR MIT

- **Authors**: Erick Tryzelaar <erick.tryzelaar@gmail.com>|David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/serde-rs/serde
- **Description**: Macros 1.1 implementation of #[derive(Serialize, Deserialize)]
- **Used by**: element-insight-binary, framework-export-binary

---

### serde_json (1.0.140) - Apache-2.0 OR MIT

- **Authors**: Erick Tryzelaar <erick.tryzelaar@gmail.com>|David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/serde-rs/json
- **Description**: A JSON serialization file format
- **Used by**: element-insight-binary, framework-export-binary

---

### serde_urlencoded (0.7.1) - Apache-2.0 OR MIT

- **Authors**: Anthony Ramine <n.oxyde@gmail.com>
- **Repository**: https://github.com/nox/serde_urlencoded
- **Description**: `x-www-form-urlencoded` meets Serde
- **Used by**: element-insight-binary

---

### servo_arc (0.1.1) - Apache-2.0 OR MIT

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/servo
- **Description**: A fork of std::sync::Arc with some extra functionality and without weak references
- **Used by**: element-insight-binary

---

### servo_arc (0.3.0) - Apache-2.0 OR MIT

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/servo
- **Description**: A fork of std::sync::Arc with some extra functionality and without weak references
- **Used by**: element-insight-binary, framework-export-binary

---

### sha2 (0.10.9) - Apache-2.0 OR MIT

- **Authors**: RustCrypto Developers
- **Repository**: https://github.com/RustCrypto/hashes
- **Description**: Pure Rust implementation of the SHA-2 hash function family including SHA-224, SHA-256, SHA-384, and SHA-512.
- **Used by**: framework-export-binary

---

### sharded-slab (0.1.7) - MIT

- **Authors**: Eliza Weisman <eliza@buoyant.io>
- **Repository**: https://github.com/hawkw/sharded-slab
- **Description**: A lock-free concurrent slab.
- **Used by**: element-insight-binary, framework-export-binary

---

### shared-lib (0.1.0) - MIT

- **Authors**: TestIn01 Team
- **Description**: Shared library for TestIn01 binaries
- **Used by**: element-insight-binary, framework-export-binary

---

### shlex (1.3.0) - Apache-2.0 OR MIT

- **Authors**: comex <comexk@gmail.com>|Fenhl <fenhl@fenhl.net>|Adrian Taylor <adetaylor@chromium.org>|Alex Touchet <alextouchet@outlook.com>|Daniel Parks <dp+git@oxidized.org>|Garrett Berg <googberg@gmail.com>
- **Repository**: https://github.com/comex/rust-shlex
- **Description**: Split a string into shell words, like Python's shlex.
- **Used by**: element-insight-binary, framework-export-binary

---

### signal-hook-registry (1.4.5) - Apache-2.0 OR MIT

- **Authors**: Michal 'vorner' Vaner <vorner@vorner.cz>|Masaki Hara <ackie.h.gmai@gmail.com>
- **Repository**: https://github.com/vorner/signal-hook
- **Description**: Backend crate for signal-hook
- **Used by**: element-insight-binary, framework-export-binary

---

### siphasher (0.3.11) - Apache-2.0 OR MIT

- **Authors**: Frank Denis <github@pureftpd.org>
- **Repository**: https://github.com/jedisct1/rust-siphash
- **Description**: SipHash-2-4, SipHash-1-3 and 128-bit variants in pure Rust
- **Used by**: element-insight-binary, framework-export-binary

---

### siphasher (1.0.1) - Apache-2.0 OR MIT

- **Authors**: Frank Denis <github@pureftpd.org>
- **Repository**: https://github.com/jedisct1/rust-siphash
- **Description**: SipHash-2-4, SipHash-1-3 and 128-bit variants in pure Rust
- **Used by**: element-insight-binary, framework-export-binary

---

### slab (0.4.10) - MIT

- **Authors**: Carl Lerche <me@carllerche.com>
- **Repository**: https://github.com/tokio-rs/slab
- **Description**: Pre-allocated storage for a uniform data type
- **Used by**: element-insight-binary

---

### slug (0.1.6) - Apache-2.0 OR MIT

- **Authors**: Steven Allen <steven@stebalien.com>
- **Repository**: https://github.com/Stebalien/slug-rs
- **Description**: Convert a unicode string to a slug
- **Used by**: framework-export-binary

---

### smallvec (1.15.1) - Apache-2.0 OR MIT

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/rust-smallvec
- **Description**: 'Small vector' optimization: store up to a small number of items on the stack
- **Used by**: element-insight-binary, framework-export-binary

---

### socket2 (0.5.10) - Apache-2.0 OR MIT

- **Authors**: Alex Crichton <alex@alexcrichton.com>|Thomas de Zeeuw <thomasdezeeuw@gmail.com>
- **Repository**: https://github.com/rust-lang/socket2
- **Description**: Utilities for handling networking sockets with a maximal amount of configuration possible intended.
- **Used by**: element-insight-binary, framework-export-binary

---

### stable_deref_trait (1.2.0) - Apache-2.0 OR MIT

- **Authors**: Robert Grosse <n210241048576@gmail.com>
- **Repository**: https://github.com/storyyeller/stable_deref_trait
- **Description**: An unsafe marker trait for types like Box and Rc that dereference to a stable address even when moved, and hence can be used with libraries such as owning_ref and rental.
- **Used by**: element-insight-binary, framework-export-binary

---

### string_cache (0.8.9) - Apache-2.0 OR MIT

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/string-cache
- **Description**: A string interning library for Rust, developed as part of the Servo project.
- **Used by**: element-insight-binary, framework-export-binary

---

### string_cache_codegen (0.5.4) - Apache-2.0 OR MIT

- **Authors**: The Servo Project Developers
- **Repository**: https://github.com/servo/string-cache
- **Description**: A codegen library for string-cache, developed as part of the Servo project.
- **Used by**: element-insight-binary, framework-export-binary

---

### strsim (0.11.1) - MIT

- **Authors**: Danny Guo <danny@dannyguo.com>|maxbachmann <oss@maxbachmann.de>
- **Repository**: https://github.com/rapidfuzz/strsim-rs
- **Description**: Implementations of string similarity metrics. Includes Hamming, Levenshtein, OSA, Damerau-Levenshtein, Jaro, Jaro-Winkler, and S├╕rensen-Dice.
- **Used by**: element-insight-binary, framework-export-binary

---

### sxd-document (0.2.6) - MIT

- **Authors**: Jake Goulding <jake.goulding@gmail.com>
- **Repository**: https://github.com/shepmaster/sxd-document
- **Description**: A Rust XML DOM library
- **Used by**: element-insight-binary

---

### sxd-document (0.3.2) - MIT

- **Authors**: Jake Goulding <jake.goulding@gmail.com>
- **Repository**: https://github.com/shepmaster/sxd-document
- **Description**: A Rust XML DOM library
- **Used by**: element-insight-binary

---

### sxd-xpath (0.2.1) - MIT

- **Authors**: Jake Goulding <jake.goulding@gmail.com>
- **Repository**: https://github.com/shepmaster/sxd-xpath
- **Description**: A Rust XML XPath library
- **Used by**: element-insight-binary

---

### syn (1.0.109) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/syn
- **Description**: Parser for Rust source code
- **Used by**: element-insight-binary, framework-export-binary

---

### syn (2.0.104) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/syn
- **Description**: Parser for Rust source code
- **Used by**: element-insight-binary, framework-export-binary

---

### sync_wrapper (0.1.2) - Apache-2.0

- **Authors**: Actyx AG <developer@actyx.io>
- **Repository**: https://github.com/Actyx/sync_wrapper
- **Description**: A tool for enlisting the compilerΓÇÖs help in proving the absence of concurrency
- **Used by**: element-insight-binary

---

### synstructure (0.13.2) - MIT

- **Authors**: Nika Layzell <nika@thelayzells.com>
- **Repository**: https://github.com/mystor/synstructure
- **Description**: Helper methods and macros for custom derives
- **Used by**: element-insight-binary

---

### system-configuration (0.5.1) - Apache-2.0 OR MIT

- **Authors**: Mullvad VPN
- **Repository**: https://github.com/mullvad/system-configuration-rs
- **Description**: Bindings to SystemConfiguration framework for macOS
- **Used by**: element-insight-binary

---

### system-configuration-sys (0.5.0) - Apache-2.0 OR MIT

- **Authors**: Mullvad VPN
- **Repository**: https://github.com/mullvad/system-configuration-rs
- **Description**: Low level bindings to SystemConfiguration framework for macOS
- **Used by**: element-insight-binary

---

### tempfile (3.20.0) - Apache-2.0 OR MIT

- **Authors**: Steven Allen <steven@stebalien.com>|The Rust Project Developers|Ashley Mannix <ashleymannix@live.com.au>|Jason White <me@jasonwhite.io>
- **Repository**: https://github.com/Stebalien/tempfile
- **Description**: A library for managing temporary files and directories.
- **Used by**: element-insight-binary, framework-export-binary

---

### tendril (0.4.3) - Apache-2.0 OR MIT

- **Authors**: Keegan McAllister <mcallister.keegan@gmail.com>|Simon Sapin <simon.sapin@exyr.org>|Chris Morgan <me@chrismorgan.info>
- **Repository**: https://github.com/servo/tendril
- **Description**: Compact buffer/string type for zero-copy parsing
- **Used by**: element-insight-binary, framework-export-binary

---

### tera (1.20.0) - MIT

- **Authors**: Vincent Prouillet <hello@prouilletvincent.com>
- **Repository**: https://github.com/Keats/tera
- **Description**: Template engine based on Jinja2/Django templates
- **Used by**: framework-export-binary

---

### thin-slice (0.1.1) - MPL-2.0

- **Authors**: Cameron McCormack <cam@mcc.id.au>
- **Repository**: https://github.com/heycam/thin-slice
- **Description**: An owned slice that packs the slice storage into a single word when possible
- **Used by**: element-insight-binary

---

### thiserror (1.0.69) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/thiserror
- **Description**: derive(Error)
- **Used by**: element-insight-binary, framework-export-binary

---

### thiserror (2.0.12) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/thiserror
- **Description**: derive(Error)
- **Used by**: framework-export-binary

---

### thiserror-impl (1.0.69) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/thiserror
- **Description**: Implementation detail of the `thiserror` crate
- **Used by**: element-insight-binary, framework-export-binary

---

### thiserror-impl (2.0.12) - Apache-2.0 OR MIT

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/thiserror
- **Description**: Implementation detail of the `thiserror` crate
- **Used by**: framework-export-binary

---

### thread_local (1.1.9) - Apache-2.0 OR MIT

- **Authors**: Amanieu d'Antras <amanieu@gmail.com>
- **Repository**: https://github.com/Amanieu/thread_local-rs
- **Description**: Per-object thread-local storage
- **Used by**: element-insight-binary, framework-export-binary

---

### tinystr (0.8.1) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: A small ASCII-only bounded length string representation.
- **Used by**: element-insight-binary

---

### tokio (1.45.1) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tokio
- **Description**: An event-driven, non-blocking I/O platform for writing asynchronous I/O backed applications.
- **Used by**: element-insight-binary, framework-export-binary

---

### tokio-macros (2.5.0) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tokio
- **Description**: Tokio's proc macros.
- **Used by**: element-insight-binary, framework-export-binary

---

### tokio-native-tls (0.3.1) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tls
- **Description**: An implementation of TLS/SSL streams for Tokio using native-tls giving an implementation of TLS for nonblocking I/O streams.
- **Used by**: element-insight-binary

---

### tokio-stream (0.1.17) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tokio
- **Description**: Utilities to work with `Stream` and `tokio`.
- **Used by**: element-insight-binary, framework-export-binary

---

### tokio-test (0.4.4) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tokio
- **Description**: Testing utilities for Tokio- and futures-based code
- **Used by**: element-insight-binary, framework-export-binary

---

### tokio-util (0.7.15) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tokio
- **Description**: Additional utilities for working with Tokio.
- **Used by**: element-insight-binary

---

### tower-service (0.3.3) - MIT

- **Authors**: Tower Maintainers <team@tower-rs.com>
- **Repository**: https://github.com/tower-rs/tower
- **Description**: Trait representing an asynchronous, request / response based, client or server.
- **Used by**: element-insight-binary

---

### tracing (0.1.41) - MIT

- **Authors**: Eliza Weisman <eliza@buoyant.io>|Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tracing
- **Description**: Application-level tracing for Rust.
- **Used by**: element-insight-binary, framework-export-binary

---

### tracing-attributes (0.1.30) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>|Eliza Weisman <eliza@buoyant.io>|David Barsky <dbarsky@amazon.com>
- **Repository**: https://github.com/tokio-rs/tracing
- **Description**: Procedural macro attributes for automatically instrumenting functions.
- **Used by**: element-insight-binary, framework-export-binary

---

### tracing-core (0.1.34) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tracing
- **Description**: Core primitives for application-level tracing.
- **Used by**: element-insight-binary, framework-export-binary

---

### tracing-log (0.2.0) - MIT

- **Authors**: Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tracing
- **Description**: Provides compatibility between `tracing` and the `log` crate.
- **Used by**: element-insight-binary, framework-export-binary

---

### tracing-subscriber (0.3.19) - MIT

- **Authors**: Eliza Weisman <eliza@buoyant.io>|David Barsky <me@davidbarsky.com>|Tokio Contributors <team@tokio.rs>
- **Repository**: https://github.com/tokio-rs/tracing
- **Description**: Utilities for implementing and composing `tracing` subscribers.
- **Used by**: element-insight-binary, framework-export-binary

---

### try-lock (0.2.5) - MIT

- **Authors**: Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/seanmonstar/try-lock
- **Description**: A lightweight atomic lock.
- **Used by**: element-insight-binary

---

### typed-arena (1.7.0) - MIT

- **Authors**: Simon Sapin <simon.sapin@exyr.org>|Nick Fitzgerald <fitzgen@gmail.com>
- **Repository**: https://github.com/SimonSapin/rust-typed-arena
- **Description**: The arena, a fast but limited type of allocator
- **Used by**: element-insight-binary

---

### typenum (1.18.0) - Apache-2.0 OR MIT

- **Authors**: Paho Lurie-Gregg <paho@paholg.com>|Andre Bogus <bogusandre@gmail.com>
- **Repository**: https://github.com/paholg/typenum
- **Description**: Typenum is a Rust library for type-level numbers evaluated at     compile time. It currently supports bits, unsigned integers, and signed     integers. It also provides a type-level array of type-level numbers, but its     implementation is incomplete.
- **Used by**: framework-export-binary

---

### ucd-trie (0.1.7) - Apache-2.0 OR MIT

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/ucd-generate
- **Description**: A trie for storing Unicode codepoint sets and maps.
- **Used by**: framework-export-binary

---

### unic-char-property (0.9.0) - Apache-2.0 OR MIT

- **Authors**: The UNIC Project Developers
- **Repository**: https://github.com/open-i18n/rust-unic/
- **Description**: UNIC ΓÇö Unicode Character Tools ΓÇö Character Property taxonomy, contracts and build macros
- **Used by**: framework-export-binary

---

### unic-char-range (0.9.0) - Apache-2.0 OR MIT

- **Authors**: The UNIC Project Developers
- **Repository**: https://github.com/open-i18n/rust-unic/
- **Description**: UNIC ΓÇö Unicode Character Tools ΓÇö Character Range and Iteration
- **Used by**: framework-export-binary

---

### unic-common (0.9.0) - Apache-2.0 OR MIT

- **Authors**: The UNIC Project Developers
- **Repository**: https://github.com/open-i18n/rust-unic/
- **Description**: UNIC ΓÇö Common Utilities
- **Used by**: framework-export-binary

---

### unic-segment (0.9.0) - Apache-2.0 OR MIT

- **Authors**: The UNIC Project Developers
- **Repository**: https://github.com/open-i18n/rust-unic/
- **Description**: UNIC ΓÇö Unicode Text Segmentation Algorithms
- **Used by**: framework-export-binary

---

### unic-ucd-segment (0.9.0) - Apache-2.0 OR MIT

- **Authors**: The UNIC Project Developers
- **Repository**: https://github.com/open-i18n/rust-unic/
- **Description**: UNIC ΓÇö Unicode Character Database ΓÇö Segmentation Properties
- **Used by**: framework-export-binary

---

### unic-ucd-version (0.9.0) - Apache-2.0 OR MIT

- **Authors**: The UNIC Project Developers
- **Repository**: https://github.com/open-i18n/rust-unic/
- **Description**: UNIC ΓÇö Unicode Character Database ΓÇö Version
- **Used by**: framework-export-binary

---

### unicode-ident (1.0.18) - (Apache-2.0 OR MIT) AND Unicode-3.0

- **Authors**: David Tolnay <dtolnay@gmail.com>
- **Repository**: https://github.com/dtolnay/unicode-ident
- **Description**: Determine whether characters have the XID_Start or XID_Continue properties according to Unicode Standard Annex #31
- **Used by**: element-insight-binary, framework-export-binary

---

### unicode-segmentation (1.12.0) - Apache-2.0 OR MIT

- **Authors**: kwantam <kwantam@gmail.com>|Manish Goregaokar <manishsmail@gmail.com>
- **Repository**: https://github.com/unicode-rs/unicode-segmentation
- **Description**: This crate provides Grapheme Cluster, Word and Sentence boundaries according to Unicode Standard Annex #29 rules.
- **Used by**: element-insight-binary, framework-export-binary

---

### unicode-width (0.2.1) - Apache-2.0 OR MIT

- **Authors**: kwantam <kwantam@gmail.com>|Manish Goregaokar <manishsmail@gmail.com>
- **Repository**: https://github.com/unicode-rs/unicode-width
- **Description**: Determine displayed width of `char` and `str` types according to Unicode Standard Annex #11 rules.
- **Used by**: element-insight-binary, framework-export-binary

---

### url (2.5.4) - Apache-2.0 OR MIT

- **Authors**: The rust-url developers
- **Repository**: https://github.com/servo/rust-url
- **Description**: URL library for Rust, based on the WHATWG URL Standard
- **Used by**: element-insight-binary

---

### utf-8 (0.7.6) - Apache-2.0 OR MIT

- **Authors**: Simon Sapin <simon.sapin@exyr.org>
- **Repository**: https://github.com/SimonSapin/rust-utf8
- **Description**: Incremental, zero-copy UTF-8 decoding with error handling
- **Used by**: element-insight-binary, framework-export-binary

---

### utf8-width (0.1.7) - MIT

- **Authors**: Magic Len <len@magiclen.org>
- **Repository**: https://github.com/magiclen/utf8-width
- **Description**: To determine the width of a UTF-8 character by providing its first byte.
- **Used by**: element-insight-binary, framework-export-binary

---

### utf8_iter (1.0.4) - Apache-2.0 OR MIT

- **Authors**: Henri Sivonen <hsivonen@hsivonen.fi>
- **Repository**: https://github.com/hsivonen/utf8_iter
- **Description**: Iterator by char over potentially-invalid UTF-8 in &[u8]
- **Used by**: element-insight-binary

---

### utf8parse (0.2.2) - Apache-2.0 OR MIT

- **Authors**: Joe Wilm <joe@jwilm.com>|Christian Duerr <contact@christianduerr.com>
- **Repository**: https://github.com/alacritty/vte
- **Description**: Table-driven UTF-8 parser
- **Used by**: element-insight-binary, framework-export-binary

---

### uuid (1.17.0) - Apache-2.0 OR MIT

- **Authors**: Ashley Mannix<ashleymannix@live.com.au>|Dylan DPC<dylan.dpc@gmail.com>|Hunar Roop Kahlon<hunar.roop@gmail.com>
- **Repository**: https://github.com/uuid-rs/uuid
- **Description**: A library to generate and parse UUIDs.
- **Used by**: element-insight-binary, framework-export-binary

---

### valuable (0.1.1) - MIT

- **Repository**: https://github.com/tokio-rs/valuable
- **Description**: Object-safe value inspection, used to pass un-typed structured data across trait-object boundaries.
- **Used by**: element-insight-binary, framework-export-binary

---

### vcpkg (0.2.15) - Apache-2.0 OR MIT

- **Authors**: Jim McGrath <jimmc2@gmail.com>
- **Repository**: https://github.com/mcgoo/vcpkg-rs
- **Description**: A library to find native dependencies in a vcpkg tree at build time in order to be used in Cargo build scripts.
- **Used by**: element-insight-binary

---

### version_check (0.9.5) - Apache-2.0 OR MIT

- **Authors**: Sergio Benitez <sb@sergio.bz>
- **Repository**: https://github.com/SergioBenitez/version_check
- **Description**: Tiny crate to check the version of the installed/running rustc.
- **Used by**: element-insight-binary, framework-export-binary

---

### walkdir (2.5.0) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/walkdir
- **Description**: Recursively walk a directory.
- **Used by**: framework-export-binary

---

### want (0.3.1) - MIT

- **Authors**: Sean McArthur <sean@seanmonstar.com>
- **Repository**: https://github.com/seanmonstar/want
- **Description**: Detect when another Future wants a result.
- **Used by**: element-insight-binary

---

### wasi (0.9.0+wasi-snapshot-preview1) - Apache-2.0 OR Apache-2.0 WITH LLVM-exception OR MIT

- **Authors**: The Cranelift Project Developers
- **Repository**: https://github.com/bytecodealliance/wasi
- **Description**: Experimental WASI API bindings for Rust
- **Used by**: element-insight-binary

---

### wasi (0.11.1+wasi-snapshot-preview1) - Apache-2.0 OR Apache-2.0 WITH LLVM-exception OR MIT

- **Authors**: The Cranelift Project Developers
- **Repository**: https://github.com/bytecodealliance/wasi
- **Description**: Experimental WASI API bindings for Rust
- **Used by**: element-insight-binary, framework-export-binary

---

### wasi (0.14.2+wasi-0.2.4) - Apache-2.0 OR Apache-2.0 WITH LLVM-exception OR MIT

- **Authors**: The Cranelift Project Developers
- **Repository**: https://github.com/bytecodealliance/wasi-rs
- **Description**: WASI API bindings for Rust
- **Used by**: element-insight-binary, framework-export-binary

---

### wasm-bindgen (0.2.100) - Apache-2.0 OR MIT

- **Authors**: The wasm-bindgen Developers
- **Repository**: https://github.com/rustwasm/wasm-bindgen
- **Description**: Easy support for interacting between JS and Rust.
- **Used by**: element-insight-binary, framework-export-binary

---

### wasm-bindgen-backend (0.2.100) - Apache-2.0 OR MIT

- **Authors**: The wasm-bindgen Developers
- **Repository**: https://github.com/rustwasm/wasm-bindgen/tree/master/crates/backend
- **Description**: Backend code generation of the wasm-bindgen tool
- **Used by**: element-insight-binary, framework-export-binary

---

### wasm-bindgen-futures (0.4.50) - Apache-2.0 OR MIT

- **Authors**: The wasm-bindgen Developers
- **Repository**: https://github.com/rustwasm/wasm-bindgen/tree/master/crates/futures
- **Description**: Bridging the gap between Rust Futures and JavaScript Promises
- **Used by**: element-insight-binary

---

### wasm-bindgen-macro (0.2.100) - Apache-2.0 OR MIT

- **Authors**: The wasm-bindgen Developers
- **Repository**: https://github.com/rustwasm/wasm-bindgen/tree/master/crates/macro
- **Description**: Definition of the `#[wasm_bindgen]` attribute, an internal dependency
- **Used by**: element-insight-binary, framework-export-binary

---

### wasm-bindgen-macro-support (0.2.100) - Apache-2.0 OR MIT

- **Authors**: The wasm-bindgen Developers
- **Repository**: https://github.com/rustwasm/wasm-bindgen/tree/master/crates/macro-support
- **Description**: The part of the implementation of the `#[wasm_bindgen]` attribute that is not in the shared backend crate
- **Used by**: element-insight-binary, framework-export-binary

---

### wasm-bindgen-shared (0.2.100) - Apache-2.0 OR MIT

- **Authors**: The wasm-bindgen Developers
- **Repository**: https://github.com/rustwasm/wasm-bindgen/tree/master/crates/shared
- **Description**: Shared support between wasm-bindgen and wasm-bindgen cli, an internal dependency.
- **Used by**: element-insight-binary, framework-export-binary

---

### wasm-streams (0.4.2) - Apache-2.0 OR MIT

- **Authors**: Mattias Buelens <mattias@buelens.com>
- **Repository**: https://github.com/MattiasBuelens/wasm-streams/
- **Description**: Bridging between web streams and Rust streams using WebAssembly
- **Used by**: element-insight-binary

---

### web-sys (0.3.77) - Apache-2.0 OR MIT

- **Authors**: The wasm-bindgen Developers
- **Repository**: https://github.com/rustwasm/wasm-bindgen/tree/master/crates/web-sys
- **Description**: Bindings for all Web APIs, a procedurally generated crate from WebIDL
- **Used by**: element-insight-binary

---

### winapi (0.3.9) - Apache-2.0 OR MIT

- **Authors**: Peter Atashian <retep998@gmail.com>
- **Repository**: https://github.com/retep998/winapi-rs
- **Description**: Raw FFI bindings for all of Windows API.
- **Used by**: element-insight-binary, framework-export-binary

---

### winapi-i686-pc-windows-gnu (0.4.0) - Apache-2.0 OR MIT

- **Authors**: Peter Atashian <retep998@gmail.com>
- **Repository**: https://github.com/retep998/winapi-rs
- **Description**: Import libraries for the i686-pc-windows-gnu target. Please don't use this crate directly, depend on winapi instead.
- **Used by**: element-insight-binary, framework-export-binary

---

### winapi-util (0.1.9) - MIT OR Unlicense

- **Authors**: Andrew Gallant <jamslam@gmail.com>
- **Repository**: https://github.com/BurntSushi/winapi-util
- **Description**: A dumping ground for high level safe wrappers over windows-sys.
- **Used by**: framework-export-binary

---

### winapi-x86_64-pc-windows-gnu (0.4.0) - Apache-2.0 OR MIT

- **Authors**: Peter Atashian <retep998@gmail.com>
- **Repository**: https://github.com/retep998/winapi-rs
- **Description**: Import libraries for the x86_64-pc-windows-gnu target. Please don't use this crate directly, depend on winapi instead.
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-core (0.61.2) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Core type support for COM and Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-implement (0.60.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: The implement macro for the windows crate
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-interface (0.59.1) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: The interface macro for the windows crate
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-link (0.1.3) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Linking for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-result (0.3.4) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Windows error handling
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-strings (0.4.2) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Windows string types
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-sys (0.48.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Rust for Windows
- **Used by**: element-insight-binary

---

### windows-sys (0.52.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Rust for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-sys (0.59.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Rust for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-sys (0.60.2) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Rust for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-targets (0.48.5) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import libs for Windows
- **Used by**: element-insight-binary

---

### windows-targets (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import libs for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows-targets (0.53.2) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import libs for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_aarch64_gnullvm (0.48.5) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary

---

### windows_aarch64_gnullvm (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_aarch64_gnullvm (0.53.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_aarch64_msvc (0.48.5) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary

---

### windows_aarch64_msvc (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_aarch64_msvc (0.53.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_i686_gnu (0.48.5) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary

---

### windows_i686_gnu (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_i686_gnu (0.53.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_i686_gnullvm (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_i686_gnullvm (0.53.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_i686_msvc (0.48.5) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary

---

### windows_i686_msvc (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_i686_msvc (0.53.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_x86_64_gnu (0.48.5) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary

---

### windows_x86_64_gnu (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_x86_64_gnu (0.53.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_x86_64_gnullvm (0.48.5) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary

---

### windows_x86_64_gnullvm (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_x86_64_gnullvm (0.53.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_x86_64_msvc (0.48.5) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary

---

### windows_x86_64_msvc (0.52.6) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### windows_x86_64_msvc (0.53.0) - Apache-2.0 OR MIT

- **Authors**: Microsoft
- **Repository**: https://github.com/microsoft/windows-rs
- **Description**: Import lib for Windows
- **Used by**: element-insight-binary, framework-export-binary

---

### winreg (0.50.0) - MIT

- **Authors**: Igor Shaula <gentoo90@gmail.com>
- **Repository**: https://github.com/gentoo90/winreg-rs
- **Description**: Rust bindings to MS Windows Registry API
- **Used by**: element-insight-binary

---

### wit-bindgen-rt (0.39.0) - Apache-2.0 OR Apache-2.0 WITH LLVM-exception OR MIT

- **Repository**: https://github.com/bytecodealliance/wit-bindgen
- **Description**: Runtime support for the `wit-bindgen` crate
- **Used by**: element-insight-binary, framework-export-binary

---

### writeable (0.6.1) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: A more efficient alternative to fmt::Display
- **Used by**: element-insight-binary

---

### xml5ever (0.17.0) - Apache-2.0 OR MIT

- **Authors**: The xml5ever project developers
- **Repository**: https://github.com/servo/html5ever
- **Description**: Push based streaming parser for xml
- **Used by**: element-insight-binary

---

### yoke (0.8.0) - Unicode-3.0

- **Authors**: Manish Goregaokar <manishsmail@gmail.com>
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Abstraction allowing borrowed data to be carried along with the backing data it borrows from
- **Used by**: element-insight-binary

---

### yoke-derive (0.8.0) - Unicode-3.0

- **Authors**: Manish Goregaokar <manishsmail@gmail.com>
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Custom derive for the yoke crate
- **Used by**: element-insight-binary

---

### zerocopy (0.8.26) - Apache-2.0 OR BSD-2-Clause OR MIT

- **Authors**: Joshua Liebow-Feeser <joshlf@google.com>|Jack Wrenn <jswrenn@amazon.com>
- **Repository**: https://github.com/google/zerocopy
- **Description**: Zerocopy makes zero-cost memory manipulation effortless. We write "unsafe" so you don't have to.
- **Used by**: element-insight-binary, framework-export-binary

---

### zerocopy-derive (0.8.26) - Apache-2.0 OR BSD-2-Clause OR MIT

- **Authors**: Joshua Liebow-Feeser <joshlf@google.com>|Jack Wrenn <jswrenn@amazon.com>
- **Repository**: https://github.com/google/zerocopy
- **Description**: Custom derive for traits from the zerocopy crate
- **Used by**: element-insight-binary, framework-export-binary

---

### zerofrom (0.1.6) - Unicode-3.0

- **Authors**: Manish Goregaokar <manishsmail@gmail.com>
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: ZeroFrom trait for constructing
- **Used by**: element-insight-binary

---

### zerofrom-derive (0.1.6) - Unicode-3.0

- **Authors**: Manish Goregaokar <manishsmail@gmail.com>
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Custom derive for the zerofrom crate
- **Used by**: element-insight-binary

---

### zerotrie (0.2.2) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: A data structure that efficiently maps strings to integers
- **Used by**: element-insight-binary

---

### zerovec (0.11.2) - Unicode-3.0

- **Authors**: The ICU4X Project Developers
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Zero-copy vector backed by a byte array
- **Used by**: element-insight-binary

---

### zerovec-derive (0.11.1) - Unicode-3.0

- **Authors**: Manish Goregaokar <manishsmail@gmail.com>
- **Repository**: https://github.com/unicode-org/icu4x
- **Description**: Custom derive for the zerovec crate
- **Used by**: element-insight-binary

---


## License Compatibility

All Rust crate licenses are compatible with the extension's MIT License with Krisu.ai Attribution, mostly being MIT, Apache 2.0, or other permissive open-source licenses.

## Compliance Status

✅ **All required license texts included**
✅ **All copyright notices included (where available in cargo-license output)**
✅ **License compatibility verified**
✅ **Ready for distribution**

---

**Last Generated**: \$(date)  
**Generated By**: cargo-license and Krisu.ai Automation
