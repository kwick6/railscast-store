This follows Railscast Episode #328 - Twitter Bootstrap Basics.

There were a couple issues when trying to follow the steps since the video was made using Rails 3 and now it's Rails 4.

The solution was to use the gem called "bootstrap-sass", however the gem isn't updated for Bootstrap 3 in production, so I used this:

gem 'bootstrap-sass', github: 'thomas-mcdonald/bootstrap-sass'

