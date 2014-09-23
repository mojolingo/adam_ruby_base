# adam_ruby_base

Docker base image for Adam Snark Rabbit Ruby application components. Used to freeze Ruby/Bundler versions and other associated dependencies, to speed up builds of downstream images and reduce duplication.

## Usage

Create a Dockerfile for applications as so:

```docker
FROM quay.io/mojolingo/adam-snark-rabbit-ruby

MAINTAINER Mojo Lingo LLC <ops@mojolingo.com>
```

Include a Gemfile and a `bin/run` in your application and away you go.
