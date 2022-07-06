# frozen_string_literal: true

source "https://rubygems.org"
gemspec

unless ENV["CI"]
  gem "byebug", require: false, platforms: :mri
  gem "yard",   require: false
end

gem "hanami-utils", "~> 2.0.alpha", require: false, git: "https://github.com/hanami/utils.git", branch: "main"
gem "hanami-router", "~> 2.0.alpha", require: false, git: "https://github.com/hanami/router.git", branch: "main"
gem "hanami-controller", "~> 2.0.alpha", require: false, git: "https://github.com/hanami/controller.git", branch: "main"
gem "hanami-cli", "~> 2.0.alpha", require: false, git: "https://github.com/hanami/cli.git", branch: "main"
gem "hanami-view", "~> 2.0.alpha", git: "https://github.com/hanami/view.git", branch: "main"

gem "hanami-devtools", require: false, git: "https://github.com/hanami/devtools.git", branch: "main"

gem "dry-files", git: "https://github.com/dry-rb/dry-files.git"
gem "dry-monitor", git: "https://github.com/dry-rb/dry-monitor.git", branch: "main"
gem "dry-system", git: "https://github.com/dry-rb/dry-system.git", branch: "prefer-local-components-when-importing"
gem "dry-container", git: "https://github.com/dry-rb/dry-container.git", branch: "accept-block-with-merge"

group :test do
  gem "dotenv"
  gem "dry-types"
  gem "saharspec"
  gem "slim"
end
