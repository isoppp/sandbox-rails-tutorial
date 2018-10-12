## HOW TO

bundle install

```
$ bundle install --without production
```

db migrate

```
$ bin/rails db:migrate
```

test

```
$ bin/rails test
```

watch & run test

```
$ bundle exec guard
```

run server

```
$ bin/rails s
```

## Note

generate & destroy

```bash
$ rails generate [controller|model] StaticPages home help
$ rails destroy  [controller|model] StaticPages home help
```

db migrate/rollback etc

```bash
$ rails db:migrate
$ rails db:rollback
$ rails db:migrate VERSION=0
$ rails db:migrate:reset
```
