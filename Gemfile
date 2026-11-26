source "https://rubygems.org"
git_source(:github) {|repo| "https://github.com/#{repo}.git" }

ruby "3.4.10"

# railsの起動時間を短縮する（標準gem）
gem "bootsnap", require: false

# # 環境毎に設定を管理する
# gem "config"

# Postgresqlに接続する
gem "pg", "~> 1.6"

# pumaサーバーを使えるようにする（標準gem）
gem "puma", ">= 5.0"

# # CORS設定を管理する
# gem "rack-cors"

# rails本体（標準gem）
gem "rails", "~> 8.1.3", ">= 8.1.3.1"

# タイムゾーン情報を提供する（標準gem）
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  # # セキュリティ脆弱性の静的解析
  # gem "brakeman", require: false

  # # gemのセキュリティ脆弱性のチェック
  # gem "bundler-audit", require: false

  # デバッグ
  gem "debug", platforms: %i[mri windows], require: "debug/prelude"

  # テスト用データを作成する
  gem "factory_bot_rails"
  gem "faker"

  # # N+1クエリの検出
  # gem "pg_query"
  # gem "prosopite"

  # RSpec を導入する
  gem "rspec-rails"

  # Rubocop を導入する
  gem "rubocop-faker"
  gem "rubocop-rails"
  gem "rubocop-rspec"
end

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
# gem "jbuilder"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Use the database-backed adapters for Rails.cache and Active Job
# gem "solid_cache"
# gem "solid_queue"

# Deploy this application anywhere as a Docker container [https://kamal-deploy.org]
# gem "kamal", require: false

# Add HTTP asset caching/compression and X-Sendfile acceleration to Puma [https://github.com/basecamp/thruster/]
# gem "thruster", require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin Ajax possible
# gem "rack-cors"
