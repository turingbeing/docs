# frozen_string_literal: true

source 'https://rubygems.org'
ruby '2.6.1'

# Choo choo 🚝 (only include the Rails gems we need)
gem "actionpack"
gem "actionview"
gem "activesupport"
gem "railties"
gem "sprockets-rails"

# Use Puma as the app server
gem 'puma'

# Use SCSS for stylesheets
gem 'sass-rails'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

# Turbolinks makes navigating your web application faster. Read more:
# https://github.com/turbolinks/turbolinks
gem 'turbolinks'

# Helps with running the server locally
gem 'foreman'

# For converting strings to URL friendly versions
gem 'stringex'

# Rendering markdown
gem 'redcarpet'

# Syntax highlighting code
gem 'rouge'

# For escaping code snippets in markdown
gem 'escape_utils'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console'
  gem 'listen'
end

group :test do
  # Who doesn't love tests!?
  gem "rspec-rails"

  # Browser testing stuff
  gem "capybara"
end
