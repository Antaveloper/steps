# Tests

## Rspec bundle
### Add rspec bundle

add following into the `Gemfile`

```
gem "rspec"
```
the run following commands

```
bundle
```

The following command generates a `spec` folder with `rails_helper.rb`, and `spec_helper.rb` files

```
rails g rspec:install
```

### Run test
To run tests:

```
rspec spec
```

## Factory bot

```
rails g factory_bot:model user
```
