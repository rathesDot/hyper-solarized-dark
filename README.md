(Customized) Solarized Dark theme for Hyper
===

![Screenshot](screenshot.png)

This is a config file for the [Solarized Dark](http://ethanschoonover.com/solarized) theme for [Hyper.app](https://hyper.is)

This is a customized version that slightly changed the hex-code for the green color.

Also it has set `Inconsolata` as font and `18px` as font size.

Above changes seemed to have the best results if your environment was `Windows 10` + `Hyper` + `Oh My Zsh` + `Agnoster Theme` + `Solarized Dark`

Also have a look at [ghosh/hyper-solarized-dark](https://github.com/ghosh/hyper-solarized-dark) which seems to be a true to original port.

## Usage

First clone this repository to the local plugins directory

```bash
$ git clone https://github.com/rathesDot/hyper-solarized-dark ~/.hyper_plugins/local/hyper-solarized-dark
```

Next add the plugin to the localPlugin array of `~/.hyper.js` configuration file.

```js
localPlugins: [
  'hyper-solarized-dark'
],
```

Finally reload Hyper to see the changes.


License
---

The [MIT License](LICENSE) (MIT). Please see License File for more information.
