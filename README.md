# 

## 相关插件生成组件命令

<pre>

# rails-rspec
rails g rspec:install

# rails-config
rails g rails_config:install

# mongoid
rails g mongoid:config

# mongoid_rails_migrations
generator:
	rails generate mongoid:migration your_migration_name_here

migrations:
	db:migrate
	db:migrate:down
	db:migrate:up
	db:rollback
	db:migrate:redo
	db:migrate:reset
	db:reseed (handled by mongoid)
	db:version

# kaminari
rails g kaminari:config

# carrierwave
rails generate uploader Base

# capistrano
bundle exec cap install


</pre>