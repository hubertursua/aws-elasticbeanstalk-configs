# aws-elasticbeanstalk-configs

Some common configs for AWS Elastic Beanstalk

## Environment

Ubuntu 14.04

## Config-Specific Notes

### bower.config

This also installs *git* and *nodejs*. Make sure you check other configs so that you don't install these redundantly.

### newrelic.config

Don't forget to put in your license key.

### nltk.config

By default, this installs all NLTK Data. Refer to [NLTK's documentation](http://www.nltk.org/data.html) and modify as needed.

### swapfile.config

It might be a good idea to run this first since having extra memory will also speed up installation of other software. Prepend the filename with a number to run it first (e.g. `00-swapfile.config`)

## License

ISC
