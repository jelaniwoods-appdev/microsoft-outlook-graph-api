# Base Rails

## Standard Workflow

 1. Start the web server by running `bin/server`.
 1. Navigate to your live application.
 1. As you work, remember to navigate to `/git` and **commit often as you work.**
 1. Create `oauch_environment_variable.rb` with the following
 ```rb
  ENV["AZURE_APP_ID"] = "********************"
  ENV["AZURE_APP_SECRET"] = "********************"
  ENV["AZURE_SCOPES"] = "openid profile email offline_access user.read calendars.read"
 ```
