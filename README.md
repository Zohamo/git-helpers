# Git Helpers

Helpers and conventions for Git workflow.

## :bookmark_tabs: Commands

Some useful commands

- `git config credential.helper store`
  This command stores credentials indefinitely on disk for use by future Git programs. [Git Credential Store](https://git-scm.com/docs/git-credential-store)

- `git branch | grep -v "develop" | xargs git branch -D`
  Remove all your local git branches except develop.

You can easily set up an alias for each command using git config. [Git Aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases)

- `git last` : `git config --global alias.last 'log -1 HEAD'`
  See the last commit easily.

## :pushpin: Commits

Prefixes with emojis for commits :

- :boom: `:boom:` First Commit or MAJOR UPDATE
- :bug: `:bug:` BUGFIX
- :toilet: `:toilet:` CLEANUP
- :wrench: `:wrench:` CONFIG
- :green_book: `:green_book:` DOC
- :star2: `:star2:` FEATURE
- :speech_balloon: `:speech_balloon:` LANGUAGE/TRANSLATION
- :truck: `:truck:` MOVE folders, files
- :zap: `:zap` PERFORMANCE
- :electric_plug: `:electric_plug:` PLUG Front/Back
- :sparkles: `:sparkles:` REFACTOR
- :lock: `:lock:` SECURITY
- :art: `:art:` STYLE
- :bookmark: `:bookmark:` TAG
- :mushroom: `:mushroom:` UPGRADE
- :construction: `:construction:` WIP

Ressources :

- Complete list of github markdown emoji markup [from Rafael Xavier de Souza](https://gist.github.com/rxaviers/7360908).
- Git Commit message Emoji [from François Parmentier](https://gist.github.com/parmentf/035de27d6ed1dce0b36a).
- An emoji guide for your commit messages [Gitmoji](https://gitmoji.carloscuesta.me/).

Articles :

- Bien nommer ses commits [from Quentin Busuttil](https://buzut.net/git-bien-nommer-ses-commits/).
