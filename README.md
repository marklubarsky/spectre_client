# Spectre ruby client

A gem to upload screenshots to [Spectre](https://github.com/wearefriday/spectre).

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'spectre_client', git: 'git@github.com:wearefriday/spectre_client.git'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install spectre_client

## Usage

Create a client object:

    client = SpectreClient::Client.new('Project Name', 'Suite Name', "http://spectre.local")

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at <https://github.com/wearefriday/spectre_client>.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
