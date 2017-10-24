# Parroter

A gRPC service that responses given message. This is a sandbox for my gRPC.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'parroter',:git => "https://github.com/kotaroito/grpc-parroter-service",:branch => 'master'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install parroter

## Usage

TODO: Write usage instructions here

## Development

    $ grpc_tools_ruby_protoc -Iproto --ruby_out=lib/parroter/pb --grpc_out=lib/parroter/pb proto/parroter.proto

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/parroter.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
