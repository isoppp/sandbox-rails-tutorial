## HOW TO

```
$ bundle install --without production
```

```
$ bin/rails db:migrate
```

```
$ bin/rails test
```

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
