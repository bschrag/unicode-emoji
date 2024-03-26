source "https://rubygems.org"

gemspec

gem "rake"
gem "unicode-version", git: "https://github.com/bschrag/unicode-version", ref: "6f45e389d6e5d962027a2e0439c3312547cd7da5"

group :development, :test do
  gem "minitest"
  gem "irb" unless RUBY_ENGINE == "jruby"
end
