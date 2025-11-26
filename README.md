# Thème NIG

Pour ajouter le thème, en ligne de commande 
```shell
git submodules add git@github.com:osunyorg/nig-theme.git themes/nig
```

Dans `config/_default/config.yaml`
```yaml
theme: nig-theme
_merge: deep
```

Dans `assets/sass/main.sass`
```sass
@import "nig-theme/theme"
```