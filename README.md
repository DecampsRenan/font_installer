# Font installer

I created this script because I was bored to copy/paste and refresh
my fonts folders every time I download a new font.

There is only two way to use it:

```bash
# will install the fonts for the current user, in the ~/.fonts folder
$ install_font path/to/your/fonts/*.ttf

# will install the fonts for all users (globally), in /usr/share/fonts
$ sudo intall_font -g path/to/your/fonts/*.ttf 
```

## Current limitations

Now, this script can't install fonts folders. You can't do that:
```bash
$ install_font path/to/folder
```

## TODO

- [ ] Allow a user to install fonts from a folder

## Contributing

Just send a pull request/issue ;)
