# SmartThingsAPI
Groovy File for SmartThings API Integration

### SmartThings API setup

1) Navigate to the SmartThings API website. Register a new account (or login if you already have an account).
2) Once logged in, click on My SmartApps. This will show a list of the current SmartApps installed (it could be blank for new accounts).
3) Click the New SmartApp button. The "New SmartApp" form page will appear.
4) Enter name: `Developer API`
5) Enter namespace: `smartthings`
6) Enter author: `SmartThings`
7) Enter description: `SmartApp API for developers`
7) Under "Oauth", click on Enable OAuth in Smart App. More fields will be added to the current form.
8) Take note of the "Client ID" and "Client Secret".
9) On Redirect URI, enter `http://localhost:4567/OAuthCallback`
10) The application editor will open with a basic App template. Completely delete the editor contents and replace it with the contents of SmartThingsDeveloper.groovy in this package.
11) Click the Save Button to save your changes.
12) Click the Publish Button and choose the For Me option.
13) Click the My SmartApps link again (at the top of the screen). Make sure the new App shows with status set to "Published" and OAuth set to "True".
