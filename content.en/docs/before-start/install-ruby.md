---
title: Install Ruby
weight: 2
---

# Install Ruby

## How to install Ruby

There a couple of ways to install Ruby in your computer:

* You can go to the official [page](https://www.ruby-lang.org/en/documentation/installation/#package-management-systems)
and follow the given instructions for your operation system.
* You can use the Ruby Version Manager [RVM](http://rvm.io/rvm/install#basic-install).

## Validate Ruby is installed

Once you have Ruby installed you should be able to run the following command
in the terminal:

```sh
ruby -v # => ruby 3.1.2p20 (2022-04-12 revision 4491bb740a) [x86_64-linux]
```

Also you should be able to open an interactive ruby shell using the following
command in the terminal:

```sh
irb
```
In which you can run Ruby code like this one:

```sh
irb(main):001> 1 + 1 # => 2
```
