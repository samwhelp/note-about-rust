

# demo-workspace-and-package




## Usage

run

``` sh
just build-book
```

or run

``` sh
make build-book
```



## Case

| [just](https://github.com/casey/just/tree/master) |
| --- |
| just / [justfile](https://github.com/casey/just/blob/master/justfile#L176) |
| just / [Cargo.toml](https://github.com/casey/just/blob/master/Cargo.toml#L17-L18) |
| just / crates / [generate-book](https://github.com/casey/just/tree/master/crates/generate-book) |


> just / [justfile](https://github.com/casey/just/blob/master/justfile#L176)

``` sh
cargo run --package generate-book
```

> just / [Cargo.toml](https://github.com/casey/just/blob/master/Cargo.toml#L17-L18)

``` toml
[workspace]
members = [".", "crates/*"]
```


## cargo help run

run

``` sh
cargo help run
```

show

```
...


OPTIONS
   Package Selection
       By default, the package in the current working
       directory is selected. The -p flag can be used to
       choose a different package in a workspace.

       -p spec, --package spec
           The package to run. See cargo-pkgid(1) for the SPEC
           format.

...
```



## Docs

| The Rust Programming Language |
| --- |
| [Managing Growing Projects with Packages, Crates, and Modules](https://doc.rust-lang.org/book/ch07-00-managing-growing-projects-with-packages-crates-and-modules.html) |
| [Cargo Workspaces](https://doc.rust-lang.org/book/ch14-03-cargo-workspaces.html)


| Rust 程式設計語言 |
| --- |
| [透過套件、Crate 與模組管理成長中的專案](https://rust-lang.tw/book-tw/ch07-00-managing-growing-projects-with-packages-crates-and-modules.html) |
| [Cargo 工作空間](https://rust-lang.tw/book-tw/ch14-03-cargo-workspaces.html)
