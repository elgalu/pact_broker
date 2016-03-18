# Contributing

## Setup
    rvm install .
    bundle install

## Test
    bundle exec rake

## Build
    rm -f *.gem && bundle exec gem build pact_broker.gemspec
    rm -f ~/pact_broker/vendor/*.gem && cp *.gem ~/pact_broker/vendor/
