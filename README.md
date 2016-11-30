# Lojban Dictionaries

This is a mirror [jbovlaste](http://jbovlaste.lojban.org/) dictionary exports.
We use them for providing translations for [our site](http://lojbanistan.de).

Sadly, there are no versioned databases available from the upstream dictionary site, so this repository tries to alleviate that a bit. One also needs an account in order to export programmatically (otherwise a captcha blocks access).

## exporting the data

    # env USER=<username> PASS=<password> ./print-jbovlaste-dict <language>
    env USER=hello PASS=mypass ./print-jbovlaste-dict en > en.xml


## license

The databases are in the public domain.
