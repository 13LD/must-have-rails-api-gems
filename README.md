# must-have-rails-api-gems

A collection of awesome Ruby Gems for Rails development.

The goal is to help every Rails developer to build an awesome Rails Api application/engine.


### Authentication
* [Knock](https://github.com/nsarno/knock) - Seamless JWT authentication for Rails API.
* [Devise token auth](https://github.com/lynndylanhurley/devise_token_auth) - Token based authentication for Rails JSON APIs. (Very useful on stack with angular and react) 

### Authorization
* [Pundit](https://github.com/elabs/pundit) - Pundit provides a set of helpers which guide you in leveraging regular Ruby classes and object oriented design patterns to build a simple, robust and scaleable authorization system. (Recommended)
* [cancancan](https://github.com/CanCanCommunity/cancancan) - Continuation of CanCan, the authorization Gem for Ruby on Rails.CanCan is an authorization library for Ruby on Rails which restricts what resources a given user is allowed to access. All permissions are defined in a single location (the Ability class) and not duplicated across controllers, views, and database queries. (Simpler way )

### Omniauth
* [omniauth-facebook](https://github.com/mkdynamic/omniauth-facebook)
* [omniauth-google-oauth2](https://github.com/zquestz/omniauth-google-oauth2)
* [omniauth-weibo-oauth2](https://github.com/beenhero/omniauth-weibo-oauth2)
* [omniauth-twitter](https://github.com/arunagw/omniauth-twitter)
* [omniauth-github](https://github.com/intridea/omniauth-github)
* [omniauth-linkedin-oauth2](https://github.com/decioferreira/omniauth-linkedin-oauth2)

### Active Record
* [PaperTrail](https://github.com/airblade/paper_trail) - PaperTrail lets you track changes to your models' data. It's good for auditing or versioning.
* [paranoia](https://github.com/rubysherpas/paranoia) - ActiveRecord plugin allowing you to hide and restore records without actually deleting them.
* [Validates](https://github.com/kaize/validates) - Validates provides collection of useful custom validators for Rails applications.

### Pagination
* [kaminari](https://github.com/amatsuda/kaminari) - A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Rails 3 and 4.

### API
* [Grape](https://github.com/ruby-grape/grape) - Microframework to create REST-ful APIs in Ruby.
* [fast_jsonapi](https://github.com/Netflix/fast_jsonapi) - Serializer brings convention over configuration to your JSON generation.
* Documentation
	* [swagger-blocks](https://github.com/fotinakis/swagger-blocks) - Define and serve live-updating Swagger JSON for Ruby apps.
	* [apiary](https://apiary.io/) - Work together to quickly design, prototype, document and test APIs.
	* [apiblueprint](https://apiblueprint.org) - API Documentation with powerful tooling.
	
### File Uploading
* [MiniMagick](https://github.com/minimagick/minimagick) - MiniMagick is a ruby wrapper for ImageMagick or GraphicsMagick command line.
* [Paperclip](https://github.com/thoughtbot/paperclip) - Easy file attachment management for ActiveRecord.

### Searching
* [pg_search](https://github.com/Casecommons/pg_search) - pg_search builds ActiveRecord named scopes that take advantage of PostgreSQL's full text search (almost enough for all apps)
* [searchkick](https://github.com/ankane/searchkick) - Intelligent search made easy with Rails and Elasticsearch.

### Scheduled/Recurrence Jobs (choose one)
* [Whenever](https://github.com/javan/whenever) - Whenever is a Ruby gem that provides a clear syntax for writing and deploying cron jobs.
* [Resque](https://github.com/resque/resque) - Redis-backed Ruby library for creating background jobs, placing them on multiple queues, and processing them later.
* [Sidekiq](https://github.com/mperham/sidekiq) - Simple, efficient background processing for Ruby.

### Environment Variables
* [Figaro](https://github.com/laserlemon/figaro) - Figaro is very simple, Heroku-friendly Rails app configuration using ENV and a single YAML file.
* [dotenv](https://github.com/bkeepers/dotenv) - Dotenv is a gem that allows you to set your environment variables in .env file, and it will load it in to ENV.

### Admin Panel
* [ActiveAdmin](http://activeadmin.info) - ActiveAdmin is a administration framework for Ruby on Rails applications.
  - [active_skin](https://github.com/rstgroup/active_skin): Flat skin for active admin.

### Logging
* [Lograge](https://github.com/roidrage/lograge) - An attempt to tame Rails' default policy to log everything.


## Coding Style
* [RuboCop](https://github.com/bbatsov/rubocop) - Rubocop is a Ruby static code analyzer. Out of the box it will enforce many of the guidelines outlined in the community [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide).
* [Rails Best Practice](https://github.com/railsbp/rails_best_practices) - Rails best practice is a code metric tool to check the quality of rails codes.

## Testing
* [rspec-rails](https://github.com/rspec/rspec-rails) - Rspec-rails is a testing framework for Rails 3.x and 4.x.
* [factory_bot](https://github.com/thoughtbot/factory_bot) - Factory_bot is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin_user, and so on), including factory inheritance.
* [factory_bot_rails](https://github.com/thoughtbot/factory_bot_rails) - Factory_bot_rails provides Rails integration for factory_bot.
* [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - Shoulda-matchers provides serveral matchers for testing common Rails functionality.
* [SimpleCov](https://github.com/colszowka/simplecov) - SimpleCov is a code coverage analysis tool for Ruby.
* [Database Cleaner](https://github.com/DatabaseCleaner/database_cleaner) - Database Cleaner is a set of strategies for cleaning your database in Ruby.Support ActiveRecord, DataMapper, Sequel, MongoMapper, Mongoid, CouchPotato, Ohm and Redis.
  
  


