# Free Cron Services

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An awesome directory of free cron services.

- [EasyCron](http://easycron.com/) - Cron Service Trusted by the Pros

Crontab syntax
--------------

A CRON expression is a string representing the schedule for a particular command to execute.  The parts of a CRON schedule are as follows:

    *    *    *    *    *    *
    -    -    -    -    -    -
    |    |    |    |    |    |
    |    |    |    |    |    + year [optional]
    |    |    |    |    +----- day of week (0 - 7) (Sunday=0 or 7)
    |    |    |    +---------- month (1 - 12)
    |    |    +--------------- day of month (1 - 31)
    |    +-------------------- hour (0 - 23)
    +------------------------- min (0 - 59)

Each of the parts supports wildcards (*), ranges (2-5) and lists (2,5,6,11).
