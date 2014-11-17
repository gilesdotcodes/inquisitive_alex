# InquisitiveAlex

A simple gem which I have used to try and create my first gem. It is a simple gem which prints a simple string: "Stop asking questions, Alex.".

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'inquisitive_alex'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install inquisitive_alex

## Usage

````
$ ruby
> require 'inquisitive_alex'
> class Alex
>   include InquisitiveAlex
> end
> alex = Alex.new
> alex.tell
````

## Contributing

1. Fork it ( https://github.com/[my-github-username]/inquisitive_alex/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
