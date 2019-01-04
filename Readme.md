This project is taken from later, and in here i am trying to revive the library.

# [Later2](http://ahmadshabib.github.io/later/)

_Later_ is a library for describing recurring schedules and calculating their future occurrences.  It supports a very flexible schedule definition including support for composite schedules and schedule exceptions. Create new schedules manually, via Cron expression, via text expressions, or using a fully chainable API.

Types of schedules supported by _Later_:

* Run a report on the last day of every month at 12 AM except in December
* Install patches on the 2nd Tuesday of every month at 4 AM
* Gather CPU metrics every 10 mins Mon - Fri and every 30 mins Sat - Sun
* Send out a scary e-mail at 13:13:13 every Friday the 13th

#### For complete documentation visit [http://bunkat.github.io/later/](http://bunkat.github.io/later/).


## Installation
Using npm:

    $ npm install later-fixed

Using bower:

    $ bower install later-fixed

## Building

To build the minified javascript files for _later_, run `npm install` to install dependencies and then:

    $ make all


## Versioning

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit [http://semver.org/](http://semver.org/).

## Bug tracker

Have a bug or a feature request? [Please open a new issue](https://github.com/ahmadshabib/later/issues).

## Change Log

### Later v1.0.0
It is the same as the last version of the actual library later v1.2.0
