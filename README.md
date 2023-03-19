# description

- pxmenu is a simple POSIX sh script that creates a cli menu without external deps.

# usage

```sh
./pxmenu <filename>
./pxmenu "string\nstring\nstring..."
```

- Do not pipe anything into the menu, since stdin could break stty mod.

- Format your files like this:

```sh
option1
option2
option3
```

![preview](https://raw.githubusercontent.com/iruzo/pxmenu/main/assets/preview.gif)
