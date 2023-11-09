# AAU P1 project (Group 4)

## Prerequisites

Make sure that you have [`textidote`](https://sylvainhalle.github.io/textidote/) installed on your system, so that you
can lint the project files before committing to the repository.

### TeXtidote usage

The `textidote` executable should be run in the project directory.
It will read the contents of the [`.textidote`](./.textidote) configuration file and use them as the arguments for the
program.
The `TeXtidote` GitHub Action reads the same configuration file and thus uses the same options when running `TeXtidote`.

On Windows:

```shell
java -jar textidote.jar src/main.tex
```

On Unix-like operating systems:

```shell
textidote src/main.tex
```

## To do

![assignment-3](./images/assignment-3.jpg)
