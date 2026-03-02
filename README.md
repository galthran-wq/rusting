# Rusting

Rust study repo. Cargo workspace with 12 progressive modules and 7 capstone projects.

## Progress

### Modules

- [ ] **01-basics** — Variables, types, mutability, functions, control flow
- [ ] **02-ownership** — Ownership, borrowing, references, slices, lifetimes
- [ ] **03-structs-enums** — Structs, methods, enums, Option, pattern matching
- [ ] **04-error-handling** — Result, Option, `?` operator, custom errors
- [ ] **05-collections-iterators** — Vec, HashMap, iterators, for/iter/into_iter
- [ ] **06-traits-generics** — Traits, generics, trait bounds, static vs dynamic dispatch
- [ ] **07-closures** — Fn/FnMut/FnOnce, iterator adapters, map/filter/fold
- [ ] **08-smart-pointers** — Box, Rc, Arc, RefCell, Deref/Drop
- [ ] **09-concurrency** — Threads, channels, Arc+Mutex, Send/Sync, rayon
- [ ] **10-async** — async/await, tokio, futures, reqwest
- [ ] **11-macros** — macro_rules!, proc macros, derive macros
- [ ] **12-unsafe-ffi** — Raw pointers, unsafe blocks, C interop, pyo3

### Projects

- [ ] **minigrep** — Search tool (The Rust Book) — after module 05
- [ ] **py-vs-rs** — Python vs Rust benchmarks side by side — from module 05
- [ ] **toychain** — Toy blockchain from scratch — after module 09
- [ ] **raytracer** — Ray Tracing in One Weekend — after module 09
- [ ] **restapi** — REST API with axum — after module 10
- [ ] **tui-dash** — Terminal dashboard with ratatui — after module 10
- [ ] **dataproc** — Data processing CLI with rayon + pyo3 — after module 12

## Structure

```
rusting/
├── playground/              scratch space
├── 01-basics/               module crates, each with src/bin/ exercises
├── 02-ownership/
├── ...
├── 12-unsafe-ffi/
└── projects/
    ├── minigrep/
    ├── py-vs-rs/
    ├── toychain/
    ├── raytracer/
    ├── restapi/
    ├── tui-dash/
    └── dataproc/
```

Run any exercise: `cargo run -p basics --bin hello`

Run a project: `cargo run -p minigrep`

Scratch space: `cargo run -p playground`

## Resources

- [The Rust Book](https://doc.rust-lang.org/book/)
- [Rustlings](https://github.com/rust-lang/rustlings)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Exercism Rust Track](https://exercism.org/tracks/rust)
- Programming Rust (O'Reilly)
