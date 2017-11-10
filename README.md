# Hello, Twilio!

A simple application for sending text messages with Scala & [Twilio](http://twilio.com)

## Set up

Sign up for a Twilio.com account if you don't already have one: [twilio.com/console](http://www.twilio.com/console)

```
cp src/main/resources/application.conf.example src/main/resources/application.conf
```

Edit your application.conf and add your account credentials, you can find those in the [console](http://www.twilio.com/console):

![credentials.png](credentials.png)

## Run

Run using [sbt](http://www.scala-sbt.org/) as seen below:

![sbt-run.png](sbt-run.png)

Et Voilà!

![result.png](result.png)
