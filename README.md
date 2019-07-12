# mongo
Bastille Template for MongoDB Jail

 STATUS: Testing

you can add configuration details to /usr/local/etc/mongodb.conf to customize MongoDB.

For example, to run on port 9000 instead of port 27017 (the default port), add the following to mongodb.conf:

/usr/local/etc/mongodb.conf
	net:
    		port: 9000
Every time you modify mongodb.conf, you must restart MongoDB to enable the changes:

	sudo service mongod restart
