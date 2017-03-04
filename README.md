makes
=====

Makefiles for this and that...

Using a bash function like:
```bash
function makes () {
  curl --silent https://raw.githubusercontent.com/pyfidelity/makes/master/$1 | make --file=-
}
```

makes this convenient to use:
```sh
$ makes buildout

```
