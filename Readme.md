# Heroku Kibana Provider

Kibana provider for Heroku.


## Installation

You need sign-in or sign-up to Heroku.

    $ git clone https://github.com/joeartsea/kibana-provider.git my-kibana
    $ cd my-kibana
    $ heroku create
    $ git push -u heroku master
    $ heroku open

## Deployment

Add or update files in `/public`.

    $ git add .
    $ git commit -a -m 'some commit message'
    $ git push heroku master
    $ heroku open

## Notes

### Adding Basic Auth

	$ heroku config:set USER=username
	$ heroku config:set PASS=password

## License

MIT
