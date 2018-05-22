# Learn Rust

## Install Rust on Windows

Install [Visual Studio Build Tools](http://landinghub.visualstudio.com/visual-cpp-build-tools) before install rust on Windows.

Download [rustup-init.exe](https://www.rust-lang.org/en-US/install.html)

## Install Packages

### Cygwin on Windows

Must install cmake

### Bat

[bat](https://github.com/sharkdp/bat), A cat(1) clone with wings.

``` bash
$ cargo install bat
...
   Compiling syn v0.13.7
   Compiling walkdir v2.1.4
error: failed to run custom build command for `libgit2-sys v0.6.19`
process didn't exit successfully: `C:\Users\益華\AppData\Local\Temp\cargo-install.nMy1p4NasNEH\release\build\libgit2-sys-c6fb2c46a41ef350\build-script-build` (exit code: 101)
--- stdout
running: "cmake" "C:\\Users\\益華\\.cargo\\registry\\src\\github.com-1ecc6299db9ec823\\libgit2-sys-0.6.19\\libgit2" "-G" "Visual Studio 15 2017 Win64" "-DSTATIC_CRT=OFF" "-DUSE_SSH=OFF" "-DUSE_OPENSSL=OFF" "-DCURL=OFF" "-DBUILD_SHARED_LIBS=OFF" "-DBUILD_CLAR=OFF" "-DCMAKE_INSTALL_PREFIX=C:\\Users\\益華\\AppData\\Local\\Temp\\cargo-install.nMy1p4NasNEH\\release\\build\\libgit2-sys-1be57c83f1e4bfc6\\out" "-DCMAKE_C_FLAGS= /GL- /nologo /MD" "-DCMAKE_C_FLAGS_RELEASE= /GL- /nologo /MD" "-DCMAKE_CXX_FLAGS= /nologo /MD" "-DCMAKE_CXX_FLAGS_RELEASE= /nologo /MD" "-DCMAKE_BUILD_TYPE=Release"

--- stderr
fatal: Not a git repository (or any of the parent directories): .git
thread 'main' panicked at '
failed to execute command: 系統找不到指定的檔案。 (os error 2)
is `cmake` not installed?

build script failed, must exit now', C:\Users\益華\.cargo\registry\src\github.com-1ecc6299db9ec823\cmake-0.1.31\src\lib.rs:643:5
note: Run with `RUST_BACKTRACE=1` for a backtrace.

warning: build failed, waiting for other jobs to finish...
error: failed to compile `bat v0.2.3`, intermediate artifacts can be found at `C:\Users\益華\AppData\Local\Temp\cargo-install.nMy1p4NasNEH`

Caused by:
  build failed
```

## References

1. [Rust 程式設計教學：基礎概念](https://cwchen.tw/rust-prog/intro/), [Michael Chen](https://cwchen.tw/#about)
2. [Rethinking Systems Programming](http://thoughtram.io/rust-and-nickel/#/), [Christoph Burgdorf](https://twitter.com/cburgdorf)
3. [AWS SDK for Rust](https://github.com/rusoto/rusoto), [Reference](https://rusoto.github.io/rusoto/rusoto_core/index.html), [Rusto](https://github.com/rusoto)
4. [Cargo, Rust package manager](https://github.com/rust-lang/cargo)