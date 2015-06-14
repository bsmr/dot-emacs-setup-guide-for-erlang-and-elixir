# .emacs Setup Guide for Erlang and Elixir

This _setup guide_ is a collection of suggestions to turn [Emacs][GNU Emacs] into a (sort of) _complete development environment_ for [Erlang][Erlang/OTP] and [Elixir][Elixir].

It is not a complete solution like [Spacemacs][Spacemacs], but instead it _shows_ various options for setting up Your environment.

The only prerequisites are that the following components are installed on Your system:

* [Emacs][GNU Emacs] version 24.3, 24.4, 24.5
* [Erlang][Erlang/OTP] version R17, R18
* [Elixir][Elixir] version 1.x

[GNU Emacs]: http://www.gnu.org/software/emacs/
[Erlang/OTP]: http://www.erlang.org/
[Elixir]: http://elixir-lang.org/
[Spacemacs]: https://twitter.com/spacemacs

## Features

* basic things
  * setup `git` user information
* basic emacs stuff
  * user setup
  * neotree
  * projectile
  * helm
  * help-projectile
  * projective (_optional_)
  * magit
  * company
  * powerline
  * markdown-mode+
* VI for Emacs
  * EVIL (_optional_)
  * powerline-evil
* Erlang/OTP related
  * erlang-mode
  * alchemist
* Elixir related
  * elixir-mode
  * alchemist

## Prerequisite steps...

Before You clone this repository, You should check Your environment:

* Can You start Elang's shell `erl`?
  *Hint:* To terminate `erl` enter `q().` followed by `RETURN`.
* Can You start Elixir's shell `iex`?
  *Hint:* To terminate `iex` enter `CTRL+c` followed by 'a'.
* Can You start Emacs?
  *Hint:* To exit `emacs` with only keystrokes enter `CTRL+x` followed by `CTRL+c`.
* Do You know where Your `.emacs` file is?
* Do You know where Your `.gitconfig` file is?

## Files include

There are three example files:

* `dot-emacs-example`: an emacs configuration file `.emacs`
* `dot-gitconfig-example`: a git configuration file `.git`
* `dot-gitignore_global-example`: an additional file for git with default excludes `.gitignore_global`

*TBD:* There are files in an _unixish_ environment, like Linux, Ubuntu, and should be the same for Mac OS X.
       Are they also valid for Windows systems?

## Getting started...

*TBD*

