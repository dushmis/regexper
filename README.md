[![Build Status](https://travis-ci.org/javallone/regexper.png)](https://travis-ci.org/javallone/regexper)

# Regexper

# NOTE: This repo is deprecated. Development will continue on regexper.com code in the [static site codebase](https://github.com/javallone/regexper-static)

Code for the http://www.regexper.com/ site.

## Contributing

I greatly appreciate any contributions that you may have for the site. Feel free to fork the project and work on any of the reported issues, or let me know about any improvements you think would be beneficial.

When sending pull requests, please keep them focused on a single issue. I would rather deal with a dozen pull requests for a dozen issues with one change each over one pull request fixing a dozen issues. Also, I appreciate tests to be included with feature development, but for minor changes I will probably not put up much of a fuss if they're missing.

### Working with the code

While it is not necessary, I recommend using RVM for managing your ruby environment. A project .rvmrc file is provided in the repo which will switch to ruby-1.9.3-p194 and use a gemset called "regexper" to avoid polluting your global gems.

Once your environment is ready (either by using RVM or setup manually), you can install necessary requirements using bundler:

    bundle install

And run the server locally using foreman (it will be accessible at http://localhost:5000/ by default):

    foreman start

It is also recommended to run guard while developing to ensure tests continue passing:

    bundle exec guard

## License

See LICENSE.md file for licensing details.
