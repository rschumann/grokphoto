source 'http://rubygems.org'

gem 'rails', '3.1.3'

# Temporarily include earlier rack to get rid of a ruby warning.
# See: http://stackoverflow.com/questions/7624661/rake-already-initialized-constant-warning
# gem 'rack', '1.3.3'

# Needed by heroku
gem 'thin'

# Javascript
gem 'json', '~> 1.6.4'
gem 'jquery-rails', '~> 1.0.14'

# Markup / templates
gem 'rdiscount', '~> 1.6.8'
gem 'haml', '~> 3.1.4'

# Authentication
gem 'devise', '~> 1.5.3'

# Thin controllers
gem 'inherited_resources', '~> 1.3.0'

# Ordering
gem 'acts_as_list', '~> 0.1.4'

# Forms - TODO: Switch to a stable gem once the wrapper stuff is released.
gem 'simple_form', :git => 'git://github.com/plataformatec/simple_form.git', :ref => "da92c45953"

# Image uploads
gem 'carrierwave', '~> 0.5.8'
gem 'fog', '~> 0.10.0'
gem 'mini_magick', '~> 3.3'

# Paging
gem 'kaminari', '~> 0.13.0'

# Caching
gem 'dalli', '~> 1.1.4'

# Monitoring
gem 'newrelic_rpm', '~> 3.3.1'

# Scaling
gem 'daemons', '~> 1.1.5'
gem 'delayed_job', '~> 3.0.0'
gem 'delayed_job_active_record', '~> 0.3.1'
gem 'hirefireapp', '~> 0.0.5'

# Factory
gem 'factory_girl_rails', '~> 1.1.0'

# Gems used only for assets and not required
# In production environments by default.
group :assets do
  gem 'sass-rails', '~> 3.1.0'
  gem 'coffee-rails', '~> 3.1.0'
  gem 'uglifier', '~> 1.2.1'
  #gem 'haml_coffee_assets', '~> 0.7.0'
  #gem 'execjs', '~> 1.3.0'
end

group :development, :test do
  # Database
  gem 'sqlite3', '~> 1.3.5'

  # Rspec
  gem 'rspec-rails', '~> 2.7.0'
end

group :development do
  # Heroku
  gem 'heroku'
  gem 'heroku_san', '~> 1.2.3'

  # Generators
  gem 'haml-rails', '~> 0.3.4'

  # Model schema
  gem 'annotate', :git => 'git://github.com/jeremyolliver/annotate_models.git', :branch => 'rake_compatibility'
end

group :test do
  # Pretty printed test output
  gem 'turn', '~> 0.8.3', :require => false

  # Shoulda
  gem 'shoulda', '~> 2.11.3'

  # Cleanup
  gem 'database_cleaner', '~> 0.7.0'
end

group :production do
  # Database
  gem 'pg'
end