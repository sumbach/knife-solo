source :rubygems
gemspec

group :development do
  gem 'irbtools'
end

group :test do
  gem 'mocha'
  gem 'minitest', :require => 'minitest/autorun'
end

group :development, :test do
  gem 'ruby-debug19', :platforms => :mri_19
  gem 'ruby-debug', :platforms => :mri_18
  gem 'fog'
end
