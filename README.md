# Minigrep
Exemple from the book [The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html) chapter 12.

This project consists in a command line program to find text in a file. It receive two arguments, the first one is the text to search in the file, the second is the filename. For exemple:

On bash terminal:

```shell
./program_name rust rust_book.txt
```

The output is the lines that contains this text. To activate the case insensitive search, only needs to a enviroment variable called CASE_INSENSITIVE with any value that is not equal to boolean false. For exemple:

On bash terminal:

```shell
CASE_INSENSITIVE=1

./program_name rUsT rust_book.txt
```

The same output from the first exemple will be displayed.