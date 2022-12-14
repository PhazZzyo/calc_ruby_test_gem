# CalcRubyTestGem

This is a Ruby gem basic calculator. It can do basic mathematical operations like addition, subtraction, multiplication, and division mathematical calculations.

## Installation

Install the gem and add to the application's Gemfile by executing:

    $ bundle add calc_ruby_test_gem

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install calc_ruby_test_gem

## Usage

To test the calculator through irb:
# Launch IRB and load this file calc_ruby_test_gem.rb
irb -r ./lib/calc_ruby_test_gem
# Now you can pass examples in that sequance: (first_operand, second_operand, "operation")
CalcRubyTestGem::calculate(1,2,"+")
 => "1 + 2 = 3" 
CalcRubyTestGem::calculate(1,2,"-")
 => "1 - 2 = -1"

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/PhazZzyo/calc_ruby_test_gem.
