# Explore 

to-do

[![CircleCI](https://circleci.com/gh/rootstrap/rails_api_base.svg?style=svg)](https://circleci.com/gh/piloterr/explore)
[![Maintainability](https://api.codeclimate.com/v1/badges/c7923a3c46ab456d82d0/maintainability)](https://codeclimate.com/github/piloterr/explore-backend/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/c7923a3c46ab456d82d0/test_coverage)](https://codeclimate.com/github/piloterr/explore-backend/test_coverage)

## How to use

1. Clone this repo
2. Install PostgreSQL in case you don't have it
3. Create your `database.yml` and `application.yml` file
4. `bundle install`
5. `yarn install`
6. Generate a secret key with `rake secret` and paste this value into the `application.yml`.
7. `rails db:create db:migrate`
8. `rake code_analysis` and make sure all tests pass
9. `rails s`
10. You can try

## Licence

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fpiloterr%2Fexplore-backend.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fpiloterr%2Fexplore-backend?ref=badge_large)
