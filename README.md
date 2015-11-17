![][license-badge]

<div align="center">
  <a href="http://github.com/oh-my-fish/oh-my-fish">
  <img width=90px  src="https://cloud.githubusercontent.com/assets/8317250/8510172/f006f0a4-230f-11e5-98b6-5c2e3c87088f.png">
  </a>
</div>
<br>

# rsync

Rsync Alias for [Oh My Fish][omf-link] - Inspire based [oh-my-zsh/plugins/rsync](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins/rsync).

## Install

```fish
$ omf install rsync
```


## Alias

- rsync-copy: `rsync -avz --progress -h`
- rsync-move: `rsync -avz --progress -h --remove-source-files`
- rsync-update: `rsync -avzu --progress -h`
- rsync-synchronize: `rsync -avzu --delete --progress -h`

# License

[MIT][mit] © [icyleaf][author]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/icyleaf
[omf-link]:       https://www.github.com/oh-my-fish/oh-my-fish

[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
