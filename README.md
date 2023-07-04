# fish-poetry

fork of [fish-pipenv](https://github.com/sentriz/fish-pipenv) and modified for poetry.

hooks into a change in PWD to automatically launch a [Poetry](https://python-poetry.org) shell for your Poetry project

![Dec-21-2019 19-55-32.gif](doc/screen.gif)

## Installation


| manager                                          | command                                  |
| ------------------------------------------------ | ---------------------------------------- |
| [fisher](https://github.com/jorgebucaran/fisher) | `fisher install 'ryoppippi/fish-poetry'` |

## Options
Optionally you can load environment variables from a `.env` file. To do so you must `set FISH_POETRY_LOAD_ENV true`
