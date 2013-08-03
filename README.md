parallels-zsh-plugin
====================

[oh-my-zsh plugin](https://github.com/robbyrussell/oh-my-zsh) for [Parallels Desktop](http://www.parallels.com/products/desktop/).

## Install

Create a new directory in `~/.oh-my-zsh/custom/plugins` called `parallels` and clone this repo into that directory. Note: it must be named `parallels` or oh-my-zsh won't recognize that it is a valid plugin directory.

## Usage

Add `parallels` to the `plugins` list in your `~/.zshrc`.

### Tab completion on `prlctl`

Tab completion on `prlctl` is currently the only contents of this plugin, although I'm certainly open to adding additional functionality (see _Contributing_).

The tab completion is incomplete, although the basics are there: `list`, `start`, `stop`, etc.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
