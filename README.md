# Standup

Keep check of who talk in a standup random video call.

## Installation

Install gem locally

```
git clone https://github.com/arturictus/standup.git
cd standup
bundle install
rake install
```

Add the list of participants in your home directory

_~/standup.yml_

```yaml
- Dr Thomas Hall
- Dr Matthew Campbell (Matt)
- Dr Joshua Hill (Joss)
- Dr Joseph Mitchell (Joe)
- Dr James Powell (Jamie)
- Dr Samuel Russell (Rush)
- Dr Daniel Patel (Dan)
- Dr Alexander Bell (Alek)
- Dr Luke Marshall (Marsh)
- Dr Benjamin Hull (Ben)
```


## Usage

```
$ standup
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/arturictus/standup. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Code of Conduct

Everyone interacting in the Standup project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/arturictus/standup/blob/master/CODE_OF_CONDUCT.md).
