# Ruby on Rails project

## Create project

New API project
```
rails new project-name --api --database=postgresql
```

With skipping tests (add `-T`):

```
rails new demo-app --api --database=postgresql -T
```

Start DB from config file

```
rails db:create

```

## Run rails

At specific port:

```
rails s -p 8000
```
