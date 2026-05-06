# joenmarz-alias
This personal alias for my laptop can be used as submodule for
[oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).


## Installation
Alteratively, you can choose between these two methods of installation:

Method 1:
Go to `.oh-my-zsh` directory and install it as submodule:
```zsh
cd ~/.oh-my-zsh
git submodule add https://github.com/LarryMarzanJr/joenmarz-alias.git plugins/joenmarz-alias
```

Method 2:
Clone this repository:
```zsh
git clone https://github.com/LarryMarzanJr/joenmarz-alias.git ~/.joenmarz-alias
```
Then link this repository to `oh-my-zsh` plugins directory:
```zsh
ln -s ~/.joenmarz-alias ~/.oh-my-zsh/plugins/joenmarz-alias
```

## Enabling Plugin
To enable this plugin add `joenmarz-alias` to the plugins array in your `.zshrc` file:

```zsh
plugins=(... joenmarz-alias)
```

## Aliases

| Alias                  | Command                                                   |
| :--------------------- | :-------------------------------------------------------- |
| `al`                   | `cd "~/Projects/joenmarz-alias"`                          |
| `blog`                 | `cd "~/Documents/blog"`                                   |
| `mkblog`               | `mkdir "~/Documents/blog"`                                |
