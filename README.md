# Mendeley Python Skeleton #

This is a simple Python application that uses the Mendeley API.

## Getting started ##

1. Register your client at the [developer portal](http://dev.mendeley.com). Use `dummy` as your redirect URI. This will give you a client ID and secret.
2. Click on the button below to deploy the app to Heroku.  You will need to fill in the client ID and secret from the previous step.
    
    [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/matt-thomson/mendeley-python-skeleton)

3. Back at the developer portal, change your app's redirect URI to the Heroku URL with `/oauth` on the end.  For example, if your Heroku app is deployed at:
 
    `https://secure-citadel-6801.herokuapp.com`

    then your redirect URI should be:
    
    `https://secure-citadel-6801.herokuapp.com/oauth`

Your app should now be deployed.  You can now follow the instructions in the Heroku console to clone and edit the code.

## Running the app locally ##

1. Clone the app using the instructions on the "Code" tab in the Heroku console.
2. Register another client ID and secret, with the redirect URL `http://localhost:5000/oauth`.
3. Run `foreman start` to start the app, and go to `http://localhost:5000` in your browser.   

## Further reading ##

- SDK documentation: [http://mendeley-python.readthedocs.org](http://mendeley-python.readthedocs.org)
- Developer portal: [http://dev.mendeley.com](http://dev.mendeley.com)
- Flask: [http://flask.pocoo.org/](http://flask.pocoo.org/)
- Heroku: [https://devcenter.heroku.com/](https://devcenter.heroku.com/)
