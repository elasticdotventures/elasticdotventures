
turbofish (plural turbofishes) (programming) A syntactic element in Rust, ::<> , with arguments between < and > , that specifies the generic arguments of a function, method, struct, or enum in an expression.



https://forge.rust-lang.org/infra/other-installation-methods.html#which


curl -sS https://starship.rs/install.sh | sh

 eval "$(starship init bash)"


https://docs.rs/whatspp-cloud-api-rs/0.1.0/whatspp_cloud_api_rs/struct.WhatsppClient.html#method.new
https://github.com/sajuthankappan/whatsapp-cloud-api-rs


https://docs.rs/tuifw/latest/tuifw/
https://lib.rs/crates/tuifw

https://deno.land/
curl -fsSL https://deno.land/install.sh | sh
https://examples.deno.land/hello-world

https://github.com/Kniben/amen

https://rustacean.net/

https://github.com/cargo-lambda/cargo-lambda

https://github.com/rusqlite/rusqlite
https://github.com/sfackler/rust-postgres

https://docs.rs/spider/1.8.1/spider/#

https://docs.rs/tokio-console/0.1.0/tokio_console/


https://www.metaplex.com/

https://vertexclique.github.io/callysto/

https://github.com/NeuralPushkin/Dalle2-Decoder

Ch 15
Box<T> stores/points at heap
Deref trait
Rc<T> reference count
RefCell<T> weak vs. strong

Fearless concurrency allows you to write code that is free of subtle bugs and is easy to refactor without introducing new bugs.

How to create threads to run multiple pieces of code at the same time
Message-passing concurrency, where channels send messages between threads
Shared-state concurrency, where multiple threads have access to some piece of data
The Sync and Send traits, which extend Rust’s concurrency guarantees to user-defined types as well as types provided by the standard library

Ch 18
refutable   let & for 
both irrefutable     if let & while
    * but warns on irrefutable
    