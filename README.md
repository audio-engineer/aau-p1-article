# AAU P1 project (Group 4)

## Prerequisites

Make sure that you have [`textidote`](https://sylvainhalle.github.io/textidote/) installed on your system, so that you
can lint the project files before committing to the repository.

### TeXtidote usage

On Windows:

```shell
java -jar textidote.jar --check en --dict src/whitelist.txt --ignore sh:seclen,lt:en:UPPERCASE_SENTENCE_START \
--read-all src/main.tex
```

On Unix-like operating systems:

```shell
textidote --check en --dict src/whitelist.txt --ignore sh:seclen,lt:en:UPPERCASE_SENTENCE_START --read-all src/main.tex
```

## To do

![assignment-3](./images/assignment-3.jpg)
