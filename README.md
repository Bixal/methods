# Methods

The Bixal Methods are based on the stellar work done by the [18F Team](https://18f.gsa.gov/). When deciding how to document our own approach, we decided to use the 18F Methods as a starting point for building a toolkit that would reflect the way we work.

You can see [their original repository and README here](https://github.com/18F/methods). Note: This is not a fork of their repository, and because we plan on making significant changes to the content, we don't plan on merging our content back in. This is a completely separate clone.

## Getting started

### Reading the Methods online

You’re presently looking at the Methods’ GitHub (code) repository. Please [visit our homepage](https://bixal.github.io/methods/) to read the Methods online.

### Printing the Methods
To print a copy of the Methods for offline use, visit the [Methods print page](https://bixal.github.io/print/). You may need to select `file → print…` from your web browser.

### Contributing to the Methods
Coming soon.

### Running the Methods website on your local machine

You will need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). You may consider using a Ruby version manager such as [rbenv](https://github.com/sstephenson/rbenv) or [rvm](https://rvm.io/) to help ensure that Ruby version upgrades don’t mean all your [gems](https://rubygems.org/) will need to be rebuilt.

On OS X, you can use [Homebrew](http://brew.sh/) to install Ruby in `/usr/local/bin`, which may require you to update your `$PATH` environment variable:

```
shell
$ brew update
$ brew install ruby
```

To serve 18F Methods locally, using `methods` as the name of your new repository:
Run each of the following steps to get the site up and running.

```
git clone git@github.com:18F/methods
cd methods
bundle install
jekyll serve
```

You should be able to see the site at: `http://localhost:4000/`

## Current team

Bixal UX Team

## Past contributors

[18F Team](https://github.com/18F/methods#past-contributors)

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):
> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
