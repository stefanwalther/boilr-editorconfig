### Download the template

```
$ boilr template download stefanwalther/boilr-editorconfig <template-tag>
```

### Fork, modify locally and save it

```
$ git clone stefanwalther/boilr-editorconfig
```

cd into it, then

```
$ boilr template save $(PWD) <template-tag>

# e.g. 
$ boilr template save $(PWD) boilr-editorconfig
```

if you have for force the local updates, use

```
$ boilr template save $(PWD) <template-tag> -f
```

### Use it

```
$ boilr template use boilr-editorconfig .
```

### Get all templates

Get a list of all - locally installed - templates:

```
$ boilr template list
```