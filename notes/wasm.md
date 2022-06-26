# distribute oci as webassembly artificats

https://www.thorsten-hans.com/distribute-webassembly-modules-as-oci-artifacts/



# vue-wasm

https://github.com/BrockReece/vue-wasm

https://github.com/DSchroer/openscad-wasm


# deno & docker

https://medium.com/deno-the-complete-reference/running-deno-in-docker-35756ffff66d

https://deno.land/

https://www.secondstate.io/articles/deno-webassembly-rust-wasi/https://aralroca.com/blog/first-steps-webassembly-rust
* https://rustwasm.github.io/book/reference/add-wasm-support-to-crate.html
https://rustwasm.github.io/wasm-bindgen/reference/js-promises-and-rust-futures.html


## Webassembly Without The Browser Part 1
https://alexene.dev/2020/08/17/webassembly-without-the-browser-part-1.html

## 
runtime's
https://github.com/wasm3/wasm3
 Python3 │  Rust │  C/C++ │  GoLang │  Zig │  Perl
 Swift │  .Net │  Arduino, PlatformIO, Particle │ QuickJS

https://github.com/bytecodealliance/wasmtime

Standalone JIT-style runtime for WebAssembly, using Cranelift
Rust, c, c++, python, .net, go


https://github.com/bytecodealliance/wasm-micro-runtime
WebAssembly Micro Runtime (WAMR)

WebAssembly Micro Runtime (WAMR) is a lightweight standalone WebAssembly (WASM) runtime with small footprint, high performance and highly configurable features for applications cross from embedded, IoT, edge to Trusted Execution Environment (TEE), smart contract, cloud native and so on. 
X86-64, X86-32
ARM, THUMB (ARMV7 Cortex-M7 and Cortex-A15 are tested)
AArch64 (Cortex-A57 and Cortex-A53 are tested)
RISCV64, RISCV32 (RISC-V LP64 and RISC-V LP64D are tested)
XTENSA, MIPS, ARC


https://github.com/vshymanskyy/awesome-wasm-tools


https://github.com/rustwasm/book

https://rustwasm.github.io/docs/book/

wasmtime install
curl https://wasmtime.dev/install.sh -sSf | bash


trunk
Trunk is a WASM web application bundler for Rust. Trunk uses a simple, optional-config pattern for building & bundling WASM, JS snippets & other assets (images, css, scss) via a source HTML file.
https://github.com/thedodd/trunk


Kevin Hoffman -- Building a containerless future with webassembly
https://www.youtube.com/watch?v=vqBtoPJoQOE\

https://github.com/appcypher/awesome-wasm-runtimes

wasmtime docs
https://docs.wasmtime.dev/examples-profiling.html

https://rustwasm.github.io/docs/book/
https://rustwasm.github.io/docs/wasm-bindgen/

https://arxiv.org/pdf/2111.01947.pdf

* https://arxiv.org/pdf/2111.01947.pdf
    - NDP near data processing, PIM processing in memory
    - CSA: computational storage array
    - eBPF: register based ebpf bytecode



* wascc (pronounced 'wask')
    - 
    - a lot of the links are broken now!
    - wascc.dev
    - https://slides.com/autodidaddict/intro-to-wascc/fullscreen

- package manager
    - gantry
        * Gantry (waSCC Module Registry) Client CLI
        * https://crates.io/crates/gantry/0.0.9/dependencies
    - no module / package manager?
    - wasmoci ??


# RuST WASM
- evaluate of webassembly and ebpf as offloading mechanisms
* https://blog.nodraak.fr/2020/07/rust-wasm-2-hello-world/[A
- wasm-pack expects project to be a library, not executable
- can use
[lib]
crate-type = ["cdylib"]
path = "src/main.rs"

Second, we need (at least) two dependencies: wasm-bindgen and web-sys. The first one does not have any particularities, but the second one, web-sys, does. It is used to access JavaScript APIs.
👍 really good article.


## AssemblyLift
- https://dev.to/dotxlem/assemblylift-v0-2-preview-rpc-based-io-modules-2d38
- https://github.com/akkoro/assemblylift
- #assemblylift:matrix.org.
- https://c4model.com/

## waPC implementation for Rust
waPC is a protocol for communicating in and out of WebAssembly. This repository contains the Rust implementations for waPC hosts, guests, compatible codecs, and implementations for wasmtime and wasm3 engines.

https://github.com/wapc/wapc-rs

