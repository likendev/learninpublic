# Basics of Fedora

## Installing rpm packages
```zsh
sudo dnf localinstall <packages>.rpm
```

## Remove packages
```zsh
sudo dnf remove <package_name>
```

## List installed packages
```zsh
sudo dnf list installed
```

## Remove packages no longer needed
```zsh
sudo dnf autoremove
```
