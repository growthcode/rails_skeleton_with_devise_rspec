== README

Used this site to reference a lot of what I built: http://www.launchacademy.com/codecabulary/learn-rails/how-to-create-a-rails-app

<h2> Things left to do on a new app: </h2>
* Tell git to add Github as the origin for the 'master' branch
  * git remote add origin "git@github.com:<username>/<new_app>.git"

* Push the local repository up to Github (the remote repository)
  * git push origin master

* Set up Devise (or remove it):
  * http://guides.railsgirls.com/devise/
  * https://github.com/plataformatec/devise
  * http://stackoverflow.com/questions/3692905/adding-additional-field-and-validation-to-devise-view-model-in-rails-app


* create models / scaffold / migrations
* rake db:migrate ; rake db:rollback ; rake db:migrate
  * Use this command to double check that your tables / migrations are correctly configured. This is a best practices sort of deal. If you're using zsh, I'd highly recommend making an alias for this command!

* Change README.rdoc, commit and push the change
  * Replace default info with info relevant to your app

<h2> Things to do ongoing: </h2>


* RSpec: rake db:test:prepare
  * This command generates the test environment that Rspec uses. You’ll need to redo this command if you make any new migrations

<h2> Deploy to Heroku </h2>
* Create a new app with subdomain at Heroku
  * $ heroku create --stack cedar
* Push the app to Heroku
  * $ git push heroku master
