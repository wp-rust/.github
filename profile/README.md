# 🦀 WordPress and Rust (wp-rust)

High-performance, memory-safe Rust implementations of WordPress core packages.

Welcome to wp-rust! We are an open-source community dedicated to bridging the gap between the world's most popular CMS and the unparalleled speed, concurrency, and memory safety of Rust.

Whether you are building blazing-fast headless frontends, secure backend microservices, or high-performance CLI tools, wp-rust provides the foundational crates you need to interact with and extend the WordPress ecosystem.

# 🎯 Our Mission

Our goal is to fork, port, and reimplement key aspects of WordPress architecture into modular Rust crates. We focus on:

Performance: Drastically reducing overhead for parsing, data manipulation, and API interactions.

Safety: Leveraging Rust's compiler to eliminate null pointer dereferences and memory leaks.

Interoperability: Seamlessly connecting Rust applications (like WebAssembly modules, CLI tools, or external APIs) with existing WordPress instances.

# 📦 Featured Packages

Here are the primary crates maintained by this organization.

wp-blocks-rs A high-speed Gutenberg block parser and stringifier. Parse block grammar (<!-- wp:paragraph -->...<!-- /wp:paragraph -->) into a structured Rust AST for headless rendering or data analysis.

wp-hooks-rs An event-driven pub/sub system modeled after the WordPress Actions and Filters API, allowing you to build extensible Rust applications using familiar WordPress paradigms.

# 🚀 Getting Started

To use any of our packages, simply add them to your project's Cargo.toml. For example, to interact with the WordPress REST API:

[dependencies]
wp-api-rs = "0.1.0"
tokio = { version = "1", features = ["full"] }


Check the individual repository README.md files for specific usage examples, documentation, and API references. All official documentation is also published on docs.rs.

# 🤝 Contributing

We welcome contributions from both the Rust and WordPress communities! You don't need to be a Rust expert to help out. Here is how you can contribute:

Report Bugs: Open an issue in the relevant repository.

Request Features: Have an idea for a WordPress PHP function that needs a Rust port? Let us know.

Submit PRs: Check our good first issue tags across our repositories.

Please read our Contribution Guidelines and adhere to our Code of Conduct before submitting a pull request.

# 📜 License

Unless otherwise stated, all code in the wp-rust organization is dual-licensed under the MIT and Apache 2.0 licenses, making it fully compatible with the broader Rust ecosystem.

Disclaimer: wp-rust is an independent open-source project and is not affiliated with, maintained, or endorsed by the WordPress Foundation or Automattic.
