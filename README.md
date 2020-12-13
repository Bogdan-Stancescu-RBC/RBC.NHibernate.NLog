# RBC.NHibernate.NLog

This is [RBC](http://rbc.com.ro/)'s really simple, bare-bones package which bridges [NHibernate](https://nhibernate.info/)'s messages to [NLog](https://nlog-project.org/).
No other middleware needed, no other dependencies, no messing around with CommonLogging or anything else.

## Usage
Just add this line just before instantiating your NHibernate session factory:

`NHibernateLogger.SetLoggersFactory(new NLogLoggerFactory());`

That's it. Have fun!