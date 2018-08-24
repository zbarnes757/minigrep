### MINIGREP

---

This is my first command line application with Rust. Trying to learn the ins and outs by following the [book](https://doc.rust-lang.org/stable/book/second-edition/).

To run:

```bash
$ cargo run to poem.txt
    Finished dev [unoptimized + debuginfo] target(s) in 0.03s
     Running `target/debug/minigrep to poem.txt`
Are you nobody, too?
How dreary to be somebody!
```

or for case insensitive search:

```bash
$ CASE_INSENSITIVE=1 cargo run to poem.txt
    Finished dev [unoptimized + debuginfo] target(s) in 0.03s
     Running `target/debug/minigrep to poem.txt`
Are you nobody, too?
How dreary to be somebody!
To tell your name the livelong day
To an admiring bog!
```
