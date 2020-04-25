# docker-rubyonrails-postgres

1 - docker build .

2 - docker-compose run web rails new .  --database=postgresql
  - rename database.samble.yml and change database.yml

3 - docker-compose build

4 - docker-compose up

5 - docker-compose run web rails db:create