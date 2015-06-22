Very simple rails application using JQuery-UI
=========

The running application is hosted at: [cins465.us/jqui_demo](http://cins465.us/jqui_demo)

Files changed after **$ rails new**

[jqui_demo/Gemfile](https://github.com/tysonhenry/jqui_demo/blob/master/Gemfile) to add gem 'jquery-ui-rails'

[jqui_demo/config/routes.rb](https://github.com/tysonhenry/jqui_demo/blob/master/config/routes.rb) to make home#index the root page

[jqui_demo/app/assets/stylesheets/application.css](https://github.com/tysonhenry/jqui_demo/blob/master/app/assets/stylesheets/application.css) to include jquery-ui CSS

[jqui_demo/app/assets/javascripts/application.js](https://github.com/tysonhenry/jqui_demo/blob/master/app/assets/javascripts/application.js) to include jquery-ui JS

Files created after **$ rails new**

[jqui_demo/app/assets/javascripts/home.js](https://github.com/tysonhenry/jqui_demo/blob/master/app/assets/javascripts/home.js) for jquery-ui functions

[jqui_demo/app/views/home/index.html.erb](https://github.com/tysonhenry/jqui_demo/blob/master/app/views/home/index.html.erb) to use jquery-ui

[jqui_demo/app/controllers/home_controller.rb](https://github.com/tysonhenry/jqui_demo/blob/master/app/controllers/home_controller.rb) to provide index controller
