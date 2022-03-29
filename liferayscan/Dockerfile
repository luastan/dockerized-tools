FROM ruby:3

RUN apt update


RUN git clone --depth 1 https://github.com/bcoles/LiferayScan.git /liferayscan

WORKDIR /liferayscan

RUN bundle install
RUN gem build LiferayScan.gemspec
RUN gem install --local LiferayScan-0.0.1.gem


ENTRYPOINT ["LiferayScan"]
