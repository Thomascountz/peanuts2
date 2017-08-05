# Peanuts2

Normally, when an app needs serious refactoring, we simply chip away at it. However, since [Peanuts](https://github.com/Thomascountz/peanuts) was only an app for me to learn Rails with, it has outlived it's usefulness. Now, Peanuts2 has come in behind it to allow me to execute and exercise my current level of understanding about how best to use Rails to solve everyday problems.

## Overview

Peanuts solves the problem of adhoc ticket sales and RSVP lists for events. 

As an actor in NYC, I find myself wearing a producer hat more often than I've ever bargained for. One of my jobs as a theater producer is to sell, track, and overall, manage tickets. How do we market our event? How to we collect payment? How do we verify patrons' tickets? How can we use patron data to fuel our marketing and development efforts? The answer to all of the above is Peanuts.

## Installation
- Fork this repo
- `$ cd peanuts`
- `$ bundle install`
- Make sure your local PostgreSQL server is running
- `$ rails db:create`
- `$ rails db:migrate`
- `$ rails db:migrate RAILS_ENV=test`
- `$ rspec`
- `$ rails s`
- Navigate to `localhost:3000` in your broswer
