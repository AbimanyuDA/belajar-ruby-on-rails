# Rails Task Manager

A simple, lightweight Task Manager application built with Ruby on Rails 8.1 and SQLite.

## System Requirements
- **Ruby version**: 4.0.1
- **Rails version**: 8.1.3
- **Database**: SQLite3

## Getting Started

Follow these steps to run the application locally on your Mac:

### 1. Install Dependencies
Run bundler to install all required gem dependencies:
```bash
/opt/homebrew/opt/ruby/bin/bundle install
```

### 2. Setup Database & Run Migrations
Initialize the development and test databases:
```bash
/opt/homebrew/opt/ruby/bin/bundle exec rails db:migrate
/opt/homebrew/opt/ruby/bin/bundle exec rails db:migrate RAILS_ENV=test
```

### 3. Run the Test Suite
Ensure everything is working correctly by running the built-in test suite:
```bash
/opt/homebrew/opt/ruby/bin/bundle exec rails test
```

### 4. Start the Rails Server
Start the local Puma development server:
```bash
/opt/homebrew/opt/ruby/bin/bundle exec rails server
```

Once started, open your browser and navigate to:
[http://localhost:3000](http://localhost:3000) (which redirects to your tasks list).
