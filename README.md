## Marvin for Xcode

####Marvin is a plugin for Xcode, it adds a large collection of text selections, duplication and deletion commands.

Accessible via `Xcode -> Edit -> Marvin`

It includes the following commands (some might seem obvious but some need a little more detail to describe its function and value).

- Delete Line
- Duplicate Line
- Join Line
- Move To EOL and Insert LF
- Select Current Word
- Select Line Contents
  - This differs a bit from Select Line as it will exclude whitespace characters until it reaches the first valid character at both the beginning and end of the current line
- Select Next Word
- Select Previous Word
- Select Word Above
- Select Word Below
- Sort lines

As an added bonus, on save, Marvin also

- Magically cleans up whitespace on save.
- Adds a LF at the end of the document

#### Install via Alcatraz

* Install plugin and restart Xcode.

#### Build from Source

* Build the Xcode project. The plug-in will automatically be installed in `~/Library/Application Support/Developer/Shared/Xcode/Plug-ins`.

* Relaunch Xcode.

To uninstall, just remove the plugin from `~/Library/Application Support/Developer/Shared/Xcode/Plug-ins` and restart Xcode.

### Customize

You can configure Marvin's keyboard shortcuts by adding them to `System Preferences > Keyboard > Shortcuts`. Note that the `Menu Title` needs to match Marvin commands

<img src="https://raw.githubusercontent.com/zenangst/MarvinXcode/master/keyboard-shortcuts.png" alt="Keyboard Shortcuts"/>

## Contribute

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create pull request

## Thanks

A big shout out goes out to Benoît Bourdon [@benoitsan](https://github.com/benoitsan).
He made [BBUncrustifyPlugin-Xcode](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode) which includes private Xcode headers and some convenience methods that is being used in this project.
Without his tremendous work this might not have ever happened.
