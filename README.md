# volcano - Analyze your proteo mix using volcano in an unbiased manner.

## Prerequisites to run:

1. Check ruby version: `ruby -v`.
2. It should be >= 2.2.2. If you do not have ruby then run the following commands to install RVM and ruby:
```
curl -L https://get.rvm.io | bash -s stable --auto-dotfiles --autolibs=enable --rails
source /Users/<your_username>/.rvm/scripts/rvm
rvm use 2.4.0
ruby -v
```
3. Run `gem install sinatra` to install sinatra.
4. Run `ruby src/app.rb` to start the app.