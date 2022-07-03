# youtube
* https://www.youtube.com/c/JonGjengset


# awesome rust
- https://github.com/rust-unofficial/awesome-rust#resources

# cheatsheet  
https://cheats.rs/#idiomatic-rust


# https://exercism.org/tracks/rust/exercises/lucians-luscious-lasagna

# rust mentors
- https://rustbeginners.github.io/awesome-rust-mentors/
	- https://exercism.org/

- https://github.com/mre/idiomatic-rust

# troubleshooting
https://jondot.medium.com/8-steps-for-troubleshooting-your-rust-build-times-2ffc965fd13e

# remedial
* https://tourofrust.com/TOC_en.html
	static methods: below to a type use ::
	instance methods below to an instance use .


### Guide to operators, structs, impl
	- https://towardsdatascience.com/a-comprehensive-tutorial-to-rust-operators-for-beginners-11554b2c64d4
	* structs contain named fields, methods in impl block
	* https://ferrous-systems.com/blog/omg-wtf-rs-resources-to-help-you-get-started-with-rust/


#![forbid(unsafe_code)]

## throw away code	👍
	- https://vorner.github.io/2020/09/20/throw-away-code.html
	* tricks for prototyping
		- avoid unwrap, use anyhow:Error
		- cargo watch
		* https://docs.rs/itertools/latest/itertools/
		* https://docs.rs/env_logger/latest/env_logger/

# dynamic iterators

## fuzzing rust
https://blog.firosolutions.com/2020/07/superhero-rust-fuzzing/

crust of rust notes

#![warn(missing_debug_implementations, rust_2018_idioms, missing_docs)]


https://github.com/dmilford/rust-3d-demo

// https://github.com/espressif/rust-esp32-example
https://github.com/esp-rs/rust
rustup target add riscv32i-unknown-none-elf
https://github.com/esp-rs


https://rustwasm.github.io/

# doesn't work in WSL2 
https://docs.rs/hidapi/1.2.2/hidapi/

# serial passthrough in WSL2
https://community.platformio.org/t/how-to-get-platformio-to-work-through-wsl-getting-no-files-found-in-ui/13008/6

https://devblogs.microsoft.com/commandline/connecting-usb-devices-to-wsl/

https://docs.microsoft.com/en-us/windows/wsl/connect-usb

https://github.com/probe-rs/probe-rs


# K8 - krustlet.dev
https://github.com/krustlet/krustlet

# PyTorch / Machine Learning
* https://github.com/LaurentMazare/tch-rs
* https://github.com/rust-ml/linfa
* https://github.com/smartcorelib/smartcore
* https://github.com/tensorflow/rust

# discord
- https://github.com/serenity-rs/serenity

# OpenScad
https://github.com/elasticdotventures/Rust-Scad

# concurrency & parallelism
* https://github.com/crossbeam-rs/crossbeam
* https://github.com/rayon-rs/rayon
* https://capnproto.org/

# argc
https://github.com/sigoden/argc/blob/main/examples/demo.sh

# http server
- https://github.com/poem-web/poem

# http client
- https://github.com/graphql-rust/graphql-client
- soup (scraper)
	- https://gitlab.com/pwoolcoc/soup

# graphql
- https://async-graphql.github.io/async-graphql/en/index.html
- https://github.com/graphql-rust/graphql-client
- https://github.com/async-graphql/async-graphql
- https://github.com/graphql-rust/juniper

# rust github action
- https://github.com/marketplace/actions/rust-cargo-install
- https://shift.click/blog/github-actions-rust/
- 👍 https://github.com/icepuma/rust-action


# oauth
- https://github.com/HeroicKatora/oxide-auth

# topt
- https://github.com/constantoine/totp-rs

uuid
https://github.com/borngraced/meiid-rust

# wasm
https://www.secondstate.io/articles/rustwasmc/
https://github.com/WasmEdge/WasmEdge
https://www.secondstate.io/articles/lfx-mentorship-wasmedge-summer-2022/

# discord client.
https://docs.rs/serenity/0.11.2/serenity/client/struct.Client.html#method.builder

# teams message
https://www.thorsten-hans.com/send-microsoft-teams-message-oci-artifacts-azure-container-registry/

# cli structopt
https://www.thorsten-hans.com/how-to-build-clis-in-rust-with-structopt/

# https apis with reqwest
https://www.thorsten-hans.com/calling-http-apis-in-rust-with-reqwest/

# environment vars
https://www.thorsten-hans.com/working-with-environment-variables-in-rust/

# tokio: 
https://docs.rs/tokio-console/0.1.0/tokio_console/


# study
https://doc.rust-lang.org/book/ch18-01-all-the-places-for-patterns.html
https://doc.rust-lang.org/nomicon/intro.html#the-dark-arts-of-unsafe-rust
?? https://kerkour.com/black-hat-rust
https://itnext.io/container-runtime-in-rust-part-0-7af709415cda
https://www.redhat.com/sysadmin/podman-features-2


# cloudflare
https://developers.cloudflare.com/workers/tutorials/hello-world-rust/


---

# Python
* https://github.com/PyO3/PyO3
* https://github.com/dgrunwald/rust-cpython
* https://github.com/getsentry/milksnake

# Typescript
- https://github.com/neon-bindings/neon
- https://github.com/infinyon/node-bindgen (not maintained?)
- https://github.com/Testy/TestyTs

Python
https://linuxhandbook.com/dockerize-python-apps/
* Rust for a pythonista
	- https://dygalo.dev/blog/rust-for-a-pythonista-1/
	- https://dygalo.dev/blog/rust-for-a-pythonista-3/
		- build actions:
		* cargo clippy. To ensure our code follows common Rust idioms & lints;
		* cargo fmt. Provides consistent code formatting;
		* tox. Runs all Python tests.


# https://github.com/watchexec/cargo-watch


rustwash.github.io/wasm-pack

## rust lookup
tinysearch: client side document search based on bloom filters (for static site generators)

yew - full react like framework for building entire web-apps in rust

sketchup - full featured 3d modeling programming running in your browser.

Function overloading in Rust
https://medium.com/swlh/function-overloading-in-rust-d591aff64a03

how to implement a queue in rust
https://dev.to/virtualkirill/how-to-write-a-queue-in-rust-12m9

writing a windows kernel driver in rust
https://not-matthias.github.io/posts/kernel-driver-with-rust/


# Actix 3.0
* https://paper.dropbox.com/published/Announcing-Actix-Web-v3.0-QOXXb1lXgTubzXHzUq9ONY5

https://github.com/actix/actix-web
Actix Web is a powerful, pragmatic, and extremely fast web framework for Rust
https://medium.com/digitalfrontiers/microservices-in-rust-with-actix-a61bb62fee80
microservices in RUST using actix 


microservices with kafka & actix
https://medium.com/digitalfrontiers/microservices-in-rust-with-kafka-2b671295b24e

probe-run
run embedded programs just like native ones
https://ferrous-systems.com/blog/probe-run/
run rust on embedded in vscode in one click
https://ferrous-systems.com/blog/run-rust-on-your-embedded-device-from-vscode/


ebbflow client, packaging a linux package in rust
https://www.ebbflow.io/blog/vending-linux-2

https://github.com/rustwasm/wasm_game_of_life

Async Unicorns love Rust
https://blog.kdubovikov.ml/articles/rust/async-unicorns-love-rust


invariants, concrete types
https://fasterthanli.me/articles/frustrated-its-not-you-its-rust


# Pretty state machine patterns in RUST
	- https://hoverbear.org/blog/rust-state-machine-pattern/
	* a State Machine is any 'machine' which has a set of 'states' and 'transitions' defined between them.

# build a discord bot with serenity
- https://developers.facebook.com/blog/post/2020/09/30/build-discord-bot-with-rust-and-serenity/


embedded rust
https://tweedegolf.nl/en/blog/39/why-rust-is-a-great-fit-for-embedded-software

## macros for a more productive rust
	- https://www.youtube.com/watch?v=dZiWkbnaQe8
	* internal rules
	* TT Munchers
	* proc macros
	* attribute macros (i.e. #[get("/hello/<name>/<age>")] 
	* derive macros 
	* BinRead (binary file read)
	* use cpp_inherit::*;	 // wtf was that?


# flamegraph
- https://github.com/llogiq/flame
- obsolete: https://github.com/mrhooray/torch

# zero to production: telemetry 👍

	- https://www.lpalmieri.com/posts/2020-09-27-zero-to-production-4-are-we-observable-yet/
	- log crate
		* log provides five macros: trace, debug, info, warn and error.
		* actix-web Logger middleware
		- https://en.wikipedia.org/wiki/Facade_pattern
	- RUST_LOG=debug		
	- tracing crate
```rust
[dependencies]
tracing = { version = "0.1", features = ["log"] }

```
	- use tracing `span`
		https://docs.rs/tracing/0.1.19/tracing/span/index.html
	- no wait, use tracing::Instrument
		https://docs.rs/tracing/latest/tracing/trait.Instrument.html
	- no no wait, use tracing::Subscriber
		https://docs.rs/tracing/0.1.19/tracing/trait.Subscriber.html




# eBPF & RUST
	- ust library for building and running BPF/eBPF modules
	https://github.com/foniod/redbpf
	- Aya, pure rust
	https://confused.ai/posts/announcing-aya
	https://aya-rs.github.io/book/
	https://docs.cilium.io/en/stable/bpf/


# arduino code in rust
https://dev.to/creativcoder/how-to-run-rust-on-arduino-uno-40c0

# writing actix-web 100dayOfRust
https://dev.to/0xbf/day11-write-web-app-with-actix-web-100dayofrust-1lkn


# 2d/3d physics engine
https://rapier.rs/

https://nalgebra.org/
linear algebra library
\
https://nphysics.org/
2d 3d physics engine


# amethyst game engine
https://amethyst.rs/

# wasm-bindget
*bind-gen
https://github.com/rustwasm/wasm-bindgen

https://rustwasm.github.io/docs/wasm-bindgen/


# advanced data types in rust
https://blog.graystorm.com/2020/07/20/a-few-advanced-variable-types-in-rust/
Box<T> for heap storage
Cell<T> for .get .set interior mutability
RefCell<T> adds borrow checking to Cell
Rc<T> run time reference counting
Arc<T> atomic reference count, thread-safe Rc
Mutex<T> mutual exclusion lock across threads
RwLock<T> similar to RefCell, thread safe, borww() is read, borrow_mut is write()

## Tokio tutorial
* https://tokio.rs/tokio/tutorial
* TWO EASY WAYS TO TEST ASYNC FUNCTIONS IN RUST
	https://blog.x5ff.xyz/blog/async-tests-tokio-rust/
* https://www.fpcomplete.com/blog/http-status-codes-async-rust/


# Data oriented design in rust
http://jamesmcm.github.io/blog/2020/07/25/intro-dod/#en
* very advanced!


# 06-23-2022 daily log
Rustacean Station - RedisJSON

* https://www.jojolepro.com/blog/2020-08-20_event_chaining/
event chaining - useful to decouple systems 
watcher -> signal -> behavior -> behaviorSignal -> notify -> notifyEvent

* Rustacean Station: Sept 2020 / WebAssembly on Server with Krustlet
- kubelet
	- targets wasi binaries


* sheshbabu


* gentle intro to assembly with rust
	- https://lfn3.net/2020/08/03/a-gentle-intro-to-assembly-with-rust/



* zero to production rust
    - working with forms
    - https://www.lpalmieri.com/posts/2020-08-31-zero-to-production-3-5-html-forms-databases-integration-tests/

* Compile time CUDA device checking in RUST
    - https://m-decoster.github.io/2020/07/24/compile-time-cuda/
    - https://en.wikipedia.org/wiki/Tensor

    - Rust bindings for C++ api of PyTorch
        - https://github.com/LaurentMazare/tch-rs
    - Const generics
        * https://github.com/rust-lang/rfcs/blob/master/text/2000-const-generics.md
    !TBD
    
* Building and Debugging a high throughput daemon in Rust
    - https://brokenco.de/2020/07/15/high-throughput-in-rust.html
    - async/await  
    - used smol (small async runtime)   
    - Unfortunately I don’t think they’re easily debuggable at this point.
    - The “trick” to resolving the issues is seemingly as old as the cooperative multi-tasking world itself: throw some yields on it. In async-std this means task::yield_now().await;, which gives the async reactor a breather to let another task run.


* https://halite.io/
    * https://sgolem.com/blog/halite-iii-bot-development-kit-in-rust

* Serverless data ingestion with Rust and AWS SES
    - http://jamesmcm.github.io/blog/2020/08/29/rust-ses/#en
    - sending email, base64 encoding
    - s3_client, aws_lambda_events crate

* WebAssembly + RUST to Perform Serverless ML & Data Viz
    - https://www.freecodecamp.org/news/rust-webassembly-serverless-tencent-cloud/
    - ssvmup wasm toolchain (secondstate)
        * https://www.secondstate.io/articles/rustwasmc/
        * The Eigenvectors give data scientists hints on the underlying factors that drives the variance in the data. This is called Principal Component Analysis (PCA).


* The problem of safe FFI Bindings in RUST
    - https://www.abubalay.com/blog/2020/08/22/safe-bindings-in-rust
    * unsafe
        - includes raw pointers, global mutable state, untagged unions, and (notably) the ability to call functions written in other languages. 
        - two failure modes:
            * Signature mismatch because FF type Rust doesn't read .h,
            * rule violation:  “only call this once,” “only call this from one thread at a time,” “don’t pass a null pointer,” “this array argument must have at least N elements”
        - bindgen reads C or C++ headers, automatically generates signatures
        - https://github.com/dtolnay/cxx
            * https://cxx.rs/



* Inbound & outbound FFI
    - advises reading first 8 chapters of:
        https://doc.rust-lang.org/stable/nomicon/
    - https://www.possiblerust.com/guide/inbound-outbound-ffi
        * bindgen - takes a c header file as input,outputs a rust file
        - autogenerates:
        - Data types that are marked #[repr(C)], meaning they have the same hardware representation as the equivalent C data type would have.
        - Functions inside an extern "C" block, with only a function signature provided, telling the compiler that this function exists and will be provided by some other library at link time.
        - by convention: two crates X & X-sys (-sys )
    - outbound ffi: expose rust to other langs
        - approach 1: invasive outbound ffi
            * design for compatibility
            * cbindgen generates c bindings, use C data-types
        - approach 2: non-Invasive, do not expose Rust types across FFI
            * expose opaque pointers, externa language knows the name of the type
                * but NOT the contents
            * use cbindgen have a type which is public, but not #[repr(C)]
                * not guaranteed to have a layout C can understand
            * to avoid dangling pointers, put opaque RUst types on heap, leak pointer
                * Box::into_raw                

* Rust for non-systems programmers
    https://www.youtube.com/watch?v=BBvcK_nXUEg
    * eyre - https://crates.io/crates/eyre
        - idiomatic error handling
    * anyhow
        - https://github.com/dtolnay/anyhow


* optimization - making rust go brrr
	* rayon is not a magic bullet
	* wrap file io/o in a BufWriter to minimize syscalls
```rust
let fd = File::create("example.bin").expect("Failed to create file!");
let mut writer = BufWriter::new(fd);
std::io::copy(&mut; buffer, &mut; writer).expect("Failed to copy buffer!");
writer.flush().expect("Failed to write file!");

```
	* std:: alternatives can be faster 
	- parking_log - better mutex & RwLock
	- crossbeam-channel & flume alt Sender/Receiver
	- dashmap is a better solution than Arc<RwLock<Hasmap<K,V>
	- ryu & lexical - convert to & from decimal strings
	* use processor & compiler optimizations

* Deno Apps with wasm, RUST, Wasi
    - https://www.secondstate.io/articles/deno-webassembly-rust-wasi/



* how to bootstrap a rust api from scratch
    - https://www.lpalmieri.com/posts/2020-08-09-zero-to-production-3-how-to-bootstrap-a-new-rust-web-api-from-scratch/
    - 🤪: presumes actix (dated)

* how to implement a bloomfilter
    - https://onatm.dev/2020/08/10/let-s-implement-a-bloom-filter/
    - bloomfilter indicates *may* exist, but definitely does NOT exist
    - used bit_vec crate


## traits
	- Rust - understanding traits 1
	https://dev.to/brunooliveira/rust-understanding-traits-1-45md


* rust goodness case study
- https://www.linkedin.com/pulse/rust-goodness-case-study-matthew-sherborne/
    - https://doc.rust-lang.org/stable/std/convert/trait.Into.html
    - https://doc.rust-lang.org/stable/std/convert/trait.From.html
        * Used to do value-to-value conversions while consuming the input value
    - cargo clippy

* ownership in Rust part 1 & 2
- https://www.thomascountz.com/2018/07/09/ownership-in-rust-part-1
- https://www.thomascountz.com/2018/07/11/ownership-in-rust-part-2
    * references and borrowing 
        - .as_ptr()


* rustacean station: Rust 1.46 & 1.47
    😮 too advanced for me to understand! 
    - #![feature(Track_caller)]
        * enable accurate caller location reporting during panic 
        https://rust-lang.github.io/rfcs/2091-inline-semantic.html
    - LLVM 11

* rustacean station: Rust 1.48 & 1.49
    - easlier linking in rustdoc
         [`crate::foo::Foo`]
        [`Bar`](crate::bar::Bar)  
    - search aliases
        #[doc(alias = "bar")]

* https://dev.to/pancy/how-to-stick-with-rust-1gpf
    - avoid using &str (using String and clones) to avoid lifetimes
    - use cargo check

* rust for a pythonista
	-  🤯https://github.com/dgrunwald/rust-cpython
    - https://dygalo.dev/blog/rust-for-a-pythonista-2/
        * todo!() // panics with a not yet implemented
    - html5ever 
        * https://github.com/servo/html5ever
        * html5 parser
    - rust-cssparser
        * https://github.com/servo/rust-cssparser
    - kuchiki
        * html/xml tree manipulation in rust
        * https://docs.rs/kuchiki/latest/kuchiki/

# Error Handling

std::result
https://doc.rust-lang.org/std/result/index.html

## Clear explanation of RUsts module systems
	👍 seshbabu! 🥰
	- https://www.sheshbabu.com/posts/rust-module-system/
	* declare a file as a submodule using `mod` keyword in `main.rs`



## Beginner's guide to Error Handling in Rust
    - https://www.sheshbabu.com/posts/rust-error-handling/
    -  In Rust, you return something called a Result.
        * Ok(T) or Err(E)
```rust
enum Result<T, E> {
   Ok(T),
   Err(E),
}
```
* Ignore the error
	- use .unwrap(); "trust us"
* Terminate the program
	- use .expect("Can't read Cargo.toml"); 
	- see also https://doc.rust-lang.org/std/macro.panic.html
* Use a fallback value
	- use .unwrap_or("3000".to_string());
* Bubble up the error
	- use ? operator
* Bubble up multiple errors
	- Box<dyn std::error::Error></dyn>
	- https://doc.rust-lang.org/std/error/trait.Error.html#method.downcast
	- https://doc.rust-lang.org/std/error/trait.Error.html#method.downcast_mut
* Match boxed errors
* Libraries vs Applications
* Create custom errors
* Bubble up custom errors
* Match custom errors

# use rust compiler as integration testing framework
-  https://blog.logrocket.com/
	- Ian cooper 
		* 🚀: TDD, Where did it all go wrong?
			- https://www.youtube.com/watch?v=EZ05e7EMOLM
using-the-rust-compiler-as-your-integration-testing-framework/
	- write code with generic <T> types
* Result
* Future
* Option<T>
	- tagged unions
```rust
pub enum Result<T, E> {
    Ok(T),
    Err(E),
}
```
	- Types and functions CAN be annotated with #[must_use] in Rust
		* The compiler makes sure you don’t forget about variables and important return values.
		* Newtypes, newtypes, newtypes
```rust
struct UserId(Uuid)
struct OrderId(Uuid)

```
	- Custom Types
```rust
struct Percent(u8);

impl Percent {
    fn new(value: u8) -> anyhow::Result<Self> {
        if value > 100 {
            anyhow::bail!("number is too big!")
        }

        if value == 0 {
            anyhow::bail!("number is zero!")
        }

        Self(value)
    }
}

```


## face detection in node.js, with rust & webassembly
- https://dev.to/alabulei1/high-performance-and-safe-ai-as-a-service-in-node-js-43lg
- infer() function	
	- https://github.com/second-state/AI-as-a-Service/blob/master/nodejs/face_detection_service/src/lib.rs

## my fav rust signature
	- tokenize
	- https://www.brandons.me/blog/favorite-rust-function

## async iteration semantics
// too abstract!
	- https://blog.yoshuawuyts.com/async-iteration/


## data oriented design with rust
	- https://jamesmcm.github.io/blog/2020/07/25/intro-dod/
// too abstract!
Struct of arrays vs. array of structs
The cost of branching inside a hot loop
Linked List vs. Vector iteration
The cost of dynamic dispatch vs. monomorphisation

## collecting data from an api
	- https://davidmaceachern.com/posts/collecting-data-from-an-api


## no namespaces in rust is a feature
	- https://samsieber.tech/posts/2020/09/registry-structure-influence/

## learning embedded rust with Knurling-rs
	- https://ferrous-systems.com/blog/knurling-sessions-introduction/
	- https://probe.rs/
	- https://github.com/knurling-rs

## serde query
	- https://github.com/pandaman64/serde-query/
	- query language for serde, jq syntax

## awesome rust errors
	- https://www.youtube.com/watch?v=rAF8mLI0naQ
	- https://rustbeginners.github.io/awesome-rust-mentors/
	* Recoverable vs. Non Recoverable


---
https://this-week-in-rust.org/blog/archives/index.html

# Rhaiscript /rhai
embeddable scripting language for Rust
https://github.com/rhaiscript/rhai
* has Discord!


# pretty state machine patterns
https://hoverbear.org/blog/rust-state-machine-pattern/

# clear expalanation of RUST module system
https://www.sheshbabu.com/posts/rust-module-system/
ls

# Rust by Example
https://doc.rust-lang.org/rust-by-example/generics.html

# Clear explanation of Rusts module system
https://www.sheshbabu.com/posts/rust-module-system/

# Rust error handling
https://www.sheshbabu.com/posts/rust-error-handling/

