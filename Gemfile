# frozen_string_literal: true

source "https://rubygems.org"

gemspec

# jekyll과 테마를 Gemfile에서 직접 지정
gem "jekyll", "~> 4.2.0"
gem "jekyll-theme-chirpy"

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
