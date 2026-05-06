# joenmarz-alias
This personal alias for my laptop can be used as submodule for
[oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).


## Installation

To use it, go to `.oh-my-zsh` directory and install it as submodule:
```zsh
cd ~/.oh-my-zsh
git submodule add https://github.com/LarryMarzanJr/joenmarz-alias.git plugins/joenmarz-alias
```

Then add `joenmarz-alias` to the plugins array in your zshrc file:

```zsh
plugins=(... joenmarz-alias)
```

## Aliases

| Alias                  | Command                                                   |
| :--------------------- | :-------------------------------------------------------- |
| `blog`                 | `cd "~/Documents/blog"`                                   |
| `mkblog`               | `mkdir "~/Documents/blog"`                                |
