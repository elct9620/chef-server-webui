source :rubygems

gem "rails", "3.2.2"
gem "jquery-rails"
gem "haml-rails"
gem "ruby-openid"
gem "coderay"

gem "chef", :git => "git://github.com/opscode/chef.git", :branch => "master", :require => false

group(:development) do
  gem 'thin'
end

group(:production) do
  gem "unicorn", "~> 2.0.0"
  gem "therubyracer"
  gem "uglifier"
end
