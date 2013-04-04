# RailsCasts Episode #412: Fast Rails Commands

http://railscasts.com/episodes/412-fast-rails-commands

Requires Ruby 1.9.2 or higher.


### Commands used in terminal

```
gem install zeus
zeus start
zeus g model comment content
zeus rake db:migrate
zeus rake test
zeus test test/functional
time bundle exec rake db:migrate
time zeus rake db:migrate
echo .zeus.sock >> .gitignore
gem install spring
spring
spring rails g model user name
spring rake db:migrate
spring testunit test/functional
spring stop
rails console
rails console test
```

### Commands used in console

```
generate "model author name"
rake "db:migrate"
test "functional"
ActiveRecord::Base.logger = nil
```
