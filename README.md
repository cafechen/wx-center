# Description

基于微信的 web 呼叫中心

# Dependencies

* [NodeJS](http://nodejs.org/)
* [Redis](http://redis.io/)

# Installation

	$ npm install

# Configuration

See file `~/.weixin/config.json`:

	{
		"port": 4000,
		"accounts": [
			{"token":"your-wx-token1", "path":"URI that it listens to"},
			{"token":"your-wx-token2", "path":"URI that it listens to"}
		]
	}

# Testing

	$ make test

Get code coverage report by command `make test-cov`.

# Usage

	$ node app