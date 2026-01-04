# sublime-dotfiles

## How to install

```sh
git clone https://github.com/reo7sp/sublime-dotfiles

mkdir -p "$HOME/Library/Application Support/Sublime Text/Packages"
rm -rf "$HOME/Library/Application Support/Sublime Text/Packages/User"
mv sublime-dotfiles "$HOME/Library/Application Support/Sublime Text/Packages/User"
ln -sf "$HOME/Library/Application Support/Sublime Text/Packages/User" .sublime-dotfiles
```
