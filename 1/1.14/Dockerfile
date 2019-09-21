FROM ruby:2.6.0
COPY . .
WORKDIR /rails-example-project
RUN apt-get update -qq && apt-get install -y nodejs
RUN gem install bundler
RUN nodejs --version
RUN bundle install
RUN rails db:migrate
CMD ["rails", "s"]
