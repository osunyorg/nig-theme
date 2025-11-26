# Thème NIG

Pour ajouter le thème, en ligne de commande 
```shell
git submodules add git@github.com:osunyorg/nig-theme.git themes/nig
```

Dans `config/_default/config.yaml`
```yaml
theme: nig-theme
_merge: deep
theme: nig-theme
_merge: deep
params:
  plausible: numeriqueinteretgeneral.org
  debug:
     productionUrl: "https://www.numeriqueinteretgeneral.org"
```

Dans `assets/sass/main.sass`
```sass
@import "nig-theme/theme"
```