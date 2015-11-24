# coffee-club
Hackspace - The Coffee Club

## Setup

1. Clone it
	```
	git clone git@github.com:brenopolanski/coffee-club.git
	```
	
2. Install Dependencies
	
	```
	cd coffee-club && npm install
	```

3. Serve it

	```
	$ node server.js
	```
	
## Deploy on Heroku

### Heroku Button

Use the button below to instantly setup your own Coffee Club instance on Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

### Heroku manually

1. Create a new Heroku app

   ```
   heroku apps:create APP_NAME
   ```
   
2. Add Addons MongoLab

   ```
   heroku addons:add mongolab
   ```

3. Provide OAUTH_CLIENT_ID and OAUTH_CLIENT_SECRET:

   ```
   heroku config:set OAUTH_CLIENT_ID=XXXX OAUTH_CLIENT_SECRET=YYYY
   ```

4. Push changes to heroku

   ```
   git push heroku master
   ```
OR

   ```
   heroku restart
   ```

## Contributing

If you want to help, please read the [Contributing](https://github.com/brenopolanski/coffee-club/blob/master/CONTRIBUTING.md) guide.

## History

For detailed changelog, see [Releases](https://github.com/brenopolanski/coffee-club/releases).

## License

[MIT License](http://brenopolanski.mit-license.org/) © Breno Polanski
