# Apple - French keyboard on Windows

If you're on Windows and you need the apple-french keyboard layout, this project is the solution.

It gives you:

- the perfect layout
- switch `cmd` and `ctrl` to be closer to macosx (like copy/paste)
- a way to use the media controls

## Layout

At first, there's no mapping for Apple keyboard in Windows. You have to find and install the correct layout. Though, on Internet, you'll find some but they do not handle well for instance `@`, `#`, `<`, `>`. This is why I did my own layout.

Here, you've got the source of the layout and the distribuable.

If you want to edit the source, you'll need the [Microsoft Keyboard Layout Creator](http://www.microsoft.com/en-us/download/details.aspx?id=22339). You'll be able to edit `src/apple-fr.klc`.

If you want to install it, just run `dist/apple-fr/setup.exe`.

## Switch `cmd` and `ctrl`

Apple uses `cmd` as control to do copy, paste, control all the text, etc. So we need to modify `ctrl` into `cmd` and vice-versa. We'll be macosx compliant.

Simply run `dist/switch-cmd-ctrl.reg`.

## How to use media controls

Download this [app](http://uxsoft.cz/projects/apple-wireless-keyboard/), it will do the job for you.

Enjoy! And if you have any better way, or any good idea, do not hesitate to make a PR or create an issue.

## Note

- There's no `right-ctrl` (yet?). Could be sometimes a problem. Last time, I played to a specific game, it askes me to make one choice between two solutions. To make this choice, it was `left-ctrl` or `right-ctrl`. I couldn't choose the `right-ctrl` choice. Too bad.
- `left-alt` doesn't work like `right-alt`. `left-alt` is reserved to Windows. All characters are available only via `right-alt`. Do not use `left-alt` for that, you'll be surprised if not.
