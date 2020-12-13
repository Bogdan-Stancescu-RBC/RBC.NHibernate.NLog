# RBC.NHibernate.NLog

This is a really simple, bare-bones package which only bridges NHibernate's messages to NLog.
No other middleware needed, no other dependencies, no messing around with CommonLogging or anything else.

## Usage
Just add this line just before instantiating your NHibernate session factory:

`NHibernateLogger.SetLoggersFactory(new NLogLoggerFactory());`

That's it. Have fun!