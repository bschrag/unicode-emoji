source "https://rubygems.org"

gemspec

gem "rake"
gem "unicode-version", git: "https://github.com/bschrag/unicode-version", ref: "a2c652e71c86e2ac41889059e3d92c4d442a087d"

group :development, :test do
  gem "minitest"
  gem "irb" unless RUBY_ENGINE == "jruby"
end
