---
title: Install Minitest
weight: 4
---

# Install Minitest

For this book we're going to use [Minitest](https://github.com/minitest/minitest),
this testing tool was added to Ruby’s standard library.

## How to install Minitest

```sh
# Gemfile
source "https://rubygems.org"

gem "minitest"
```

```sh
bundle install
```

## Validate Minitest is installed

Once you have Minitest installed you need to create
a new file called `test_foo.rb` with the following code
(*right now don't care about it!*):

```ruby
require "minitest/autorun"

class TestFoo < Minitest::Test
  def test_foo
    assert_equal 1, 1
  end
end
```
Save the file and run the following command in the terminal:

```sh
ruby test_foo.rb
```

You should see something like these results:

```sh
Run options: --seed 6109

# Running:

.

Finished in 0.000829s, 1206.0617 runs/s, 1206.0617 assertions/s.
1 runs, 1 assertions, 0 failures, 0 errors, 0 skips
```
