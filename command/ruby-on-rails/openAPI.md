# OpenAPI

## adding rswag bundle

Add following into the `Gemfile`

```
gem "rswag"
```
the run following commands

```
bundle
```
```
rails g rswag:install
```

## Create request tests

E.g. for `cars` controller:

```
rails generate rspec:swagger cars
```

## Create swagger file
Creates `swagger.yaml` file in the `swagger` folder

```
rails rswag:specs:swaggerize
```
short alias:

```
rails rswag
```

For chosen cotroller e.g. `categories` run:

```
rails g rspec:swagger categories
```
it creates `spec/requests\categories_spec.rb` file
