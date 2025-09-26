FROM ruby:3.2

RUN apt-get update -qq && \
  apt-get install -y build-essential libpq-dev nodejs

WORKDIR /usr/src/backend

COPY ./api/Gemfile ./api/Gemfile.lock ./

# RUN gem install bundler && bundle install

# # Railsのポートを外部に公開
# EXPOSE 3000

# # サーバー起動コマンド（docker-compose.ymlで指定するなら不要）
# CMD ["rails", "server", "-b", "0.0.0.0"]
