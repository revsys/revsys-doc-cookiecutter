# REVSYS Docs Cookiecutter

This is our cookiecutter for generating REVSYS themed documentation using hugo.

**NOTE**: This cookiecutter is primarily used by our [rsdoc utility](https://github.com/revsys/rsdoc)

## Install hugo

You need to make sure [hugo](https://gohugo.io/) is installed, which for OSX is just:

    brew update
    brew install hugo

## Quickstart

Run the cookiecutter:

    cookiecutter https://github.com/revsys/revsys-doc-cookiecutter

If you used the defaults, it will create the scaffolding in `./docs/` and then all you need to do is:

    cd docs
    hugo server

And begin editing your content.

## Generating a static site version

To generate your docs into a static site just run:

    hugo

And it will build it into `./public/`

## Questions?

Talk to Frank

