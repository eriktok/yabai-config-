# Yabai and SKhd configuration

## Installation

```
brew install koekeishiya/formulae/yabai
brew install koekeishiya/formulae/skhd

cp .yabairc ~/
cp .skhdrc ~/

brew services restart yabai
brew services restart skhd 
```

### Remove config

```
rm -f "${HOME}"/.{yabai,skhd}rc
brew remove koekeishiya/formulae/yabai
brew remove koekeishiya/formulae/skhd 

```