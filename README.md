# mkdir-scripts

mkdir-scripts contains a few simple ZSH scripts to create a basic directory of files for quick tests.

## Usage

### Example

```Shell
$ mkdir-ruby foo
$ cd foo
$ ./run # Executes run.rb
```

The initial `mkdir-ruby` command will have created:

* `./foo/`
* `|--- run.rb` - The main Ruby source file for editing
* `|--- run` - A Zsh script to run `run.rb`


### Tip

Make an alias to run: `alias r="./run"`

## Languages

* Ruby
* C
* Lisp
* Python

