# tfenv
[Terraform](https://www.terraform.io/) version manager inspired by [rbenv](https://github.com/rbenv/rbenv)

## Support
Currently tfenv supports only Mac OS X because developer (@kamatama41) uses it (Yosemite 10.10.5).


## Installation
1. Check out tfenv into any path
```sh
$ git clone https://github.com/kamatama41/tfenv.git /some/path/to/tfenv
```
2. Add `/some/path/to/tfenv/bin` to your `$PATH`

This is an example of adding `.zshrc`
```
if [ -f /some/path/to/tfenv/bin/tfenv ]; then
  path=(/some/path/to/tfenv/bin $path)
fi
```

## Usage
### tfenv install
Install terraform
```sh
$ tfenv install 0.7.0
```

### tfenv use
Switch a version to use
```sh
$ tfenv use 0.7.0
```