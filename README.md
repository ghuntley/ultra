# ultra [![Build Status](https://img.shields.io/travis/domdere/ultra.svg?style=flat)](https://travis-ci.org/domdere/ultra)

TODO: Insert a Picture here of the "Street Fighter IV: Ultra" banner sometime.

If I have functions and such that I wish to add to an existing library and I want to give them a trial period to see if they are really useful before committing myself to submitting a PR for the library itself, I'll put it in a project here first.

## Usage

### Using git and mafia?

Drop the [`mafia`](https://github.com/ambiata/mafia) script next to your cabal file:

``` shell
curl -O https://raw.githubusercontent.com/ambiata/mafia/master/script/mafia && chmod +x mafia
```

Create a `lib` dir in the root of your git repo, and add `ultra` as a submodule in that directory.

Add the ultra projects you want to use to the relevant cabal files.

Build your project with:

``` shell
./mafia build
```
