#clippy-api-rust

##Installation
You’ll need the nightly version of [Rust](http://www.rust-lang.org/install.html) which will also install Cargo (Rust’s package manager). Make sure you’re on the lastest nightly! It looks like our dependencies develop on the latest build of Rust.

1. Clone the repo and cd into it
2. ``` $ cargo run ``` and the server should be running on http://127.0.0.1:6767/

##Available routes
###/hello/:thing
Returns “Hello, :thing!”
