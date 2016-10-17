## Newman

The `newman` plugin provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman) .

### Installation

1. Create a folder `newman` in your Oh-my-zsh plugin directory `~/.oh-my-zsh/plugins` and put `_newman` inside the `~/.oh-my-zsh/plugins/newman` folder.

2. Enable the plugin in your `~/.zshrc`:
  ```
  plugins=(... newman)
  ```

3. Newman requires [NodeJS](https://nodejs.org/en/) and [npm](https://www.npmjs.com/). To install newman simply run:
  ```
  npm install -g newman
  ```

4. Type `newman` into your promt and hit `TAB` to see available completion options.
