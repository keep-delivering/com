ruby("2.4.9")
source("https://rubygems.org")

gem("aasm")
gem("cancan", { require: false })
gem("haml")
gem("haml-rails")
gem("i18n-js")
gem("jbuilder", "~> 2.0")
gem("jquery-rails")
gem("jquery-ui-rails")
gem("omniauth-twitter")
gem("pg", "0.18.4")
gem("rack-cors")
gem("rails", "4.2.11.1")
gem("sprockets-es6")
gem("turbolinks")

group(:production) do
  gem("puma")
end

group(:doc) do
  gem("sdoc", "~> 0.4.0")
end

group(:development) do
  gem("foreman")
end

group(:development, :test) do
  gem("byebug")
  gem("dotenv")
  gem("guard")
  gem("guard-rails", { require: false })
  gem("guard-rspec", { require: false })
  gem("guard-teaspoon")
  gem("i18n-tasks")
  gem("render")
  gem("rspec-rails", "~> 3.0")
  gem("shotgun")
  gem("spring")
  gem("teaspoon-jasmine")
  gem("web-console", "~> 2.0")
end

group(:test) do
  gem("bundler-audit")
  gem("cucumber-rails", { require: false })
  gem("database_cleaner")
  gem("faker")
  gem("launchy")
  gem("poltergeist")
  gem("rubocop", { require: false })
  gem("selenium-webdriver")
end
