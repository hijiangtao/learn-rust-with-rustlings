# learn-rust-with-rustlings

## README (EN)

Small exercises to get you used to reading and writing Rust code. Includes practice reading and responding to compiler messages! 

This repo is my rustlings' solution collection. Hope it can help you more or less. :)

**✅Successfully compiled all rustlings exercises! All the answers can be found in corresponding folders.** For example, you can check file `exercises/strings/strings1.rs` to read my solution about `strings` chapter.

## README (CN)

rust 学习之 rustlings 训练答案集，所有训练均已完成，内容在具体的文件中可以查看，比如 `strings` 为已完成状态，则对应 `exercises/strings/strings1.rs` 文件中代码即为答案，以下为训练分章节目录。

* [x] if
* [x] functions
* [x] variables
* [x] primitive_types
* [x] strings
* [x] modules
* [x] macros
* [x] move_semantics
* [x] error_handling
* [x] threads
* [x] standard_library_types

## Manually

Basically: Clone the repository, checkout to the latest tag, run `cargo install`.

```bash
git clone https://github.com/hijiangtao/learn-rust-with-rustlings
cd learn-rust-with-rustlings
cargo install --force --path .
```

If there are installation errors, ensure that your toolchain is up to date. For the latest, run:
```bash
rustup update
```

Then, same as above, run `rustlings` to get started.

## Doing exercises

The exercises are sorted by topic and can be found in the subdirectory `rustlings/exercises/<topic>`. For every topic there is an additional README file with some resources to get you started on the topic. We really recommend that you have a look at them before you start.

The task is simple. Most exercises contain an error that keep it from compiling, and it's up to you to fix it! Some exercises are also run as tests, but rustlings handles them all the same. To run the exercises in the recommended order, execute:

```bash
rustlings watch
```

This will try to verify the completion of every exercise in a predetermined order (what we think is best for newcomers). It will also rerun automatically every time you change a file in the `exercises/` directory. If you want to only run it once, you can use:

```bash
rustlings verify
```

This will do the same as watch, but it'll quit after running.

In case you want to go by your own order, or want to only verify a single exercise, you can run:

```bash
rustlings run exercises/path/to/exercise.rs
```

In case you get stuck, there is usually a hint at the bottom of each exercise.

## Testing yourself

After every couple of sections, there will be a test that'll test your knowledge on a bunch of sections at once. These tests are found in `exercises/testN.rs`.

## Contact

[@hijiangtao](https://github.com/hijiangtao)

## LICENSE

MIT