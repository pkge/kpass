# pass

A fork of https://www.passwordstore.org/ with two additions:

 - a `--guide` option to the `generate` command that prompts the user for a
   username and url, which are then stored in json.
 - piping of lines 2+ to `jq` for pretty printing of json

I find this provides a nicer experience for my pass usage patterns.

# Install

```
brew tap pkge/tap
brew install pkge/tap/pass
```

# Future additions

It would be nice to be able to easily add fields.
Something like:

    pass update --add user=MYNAME pass-name
