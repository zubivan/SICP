Personal repo to go through SICP book.

Book from MIT EDU:
https://web.mit.edu/alexmv/6.037/sicp.pdf

Using Racket dialect of LISP instead of Scheme. See
https://racket-lang.org/ for more details.

## MacOS setup

> Assuming existance of brew.

Racket REPL

```sh
brew install racket
```

SICP language for Racket
> https://docs.racket-lang.org/sicp-manual

```sh
raco pkg install sicp
```

VSCode as an IDE, either go to
> https://code.visualstudio.com/docs/setup/mac

```sh
brew cask install visual-studio-code
```

## Racket REPL

As you coupld have guessed it's just

```sh
racket
```

Go wild from here :rocket:

### Some useful commands

Getting out of Racket REPL

```sh
(exit)
```

Running racket file

```sh
racket hello_world.rkt
```

Running racket file and staying in interactive mode

```sh
racket -it hello_world.rkt
```
