> # Deprecation notice :rotating_light:
> [I've switched to Vim](https://github.com/rafaelrinaldi/vimfiles) and don't use Sublime Text anymore. With that being said I'm no longer going to improve nor maintain this repository. Feel free to fork it and do whatever you want.

# st-snippets

List of snippets I have made for working with Sublime Text.

## Installation

```sh
git clone git@github.com:rafaelrinaldi/st-snippets.git && mv -f st-snippets ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/st-snippets
```

## Update

The snippets are updated quite often. To make sure you're running the latest version, simply run:

```sh
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/st-snippets && git pull
```

## Removing

To remove the snippets from your Sublime Text folder, run:

```sh
rm -rf ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/st-snippets
```

> If you're running Sublime Text 2, make sure you change the destination path of the commands above.

## Snippets

There are snippets available for the following languages:

* ActionScript 3
* JavaScript <small>(Snippets for working with [AMD][amd], [RequireJS][rjs], [Jasmine][jasmine], console, etc.)</small>

[amd]: https://github.com/amdjs/amdjs-api/wiki/AMD
[rjs]: https://github.com/jrburke/requirejs
[jasmine]: https://github.com/pivotal/jasmine
