# macOS german keyboard layout with yz keys switched

Are you annoyed that german keyboard layout makes using the standard <kbd>command</kbd> + <kbd>z</kbd> for `Undo` rather cumbersome? Here is a layout which switches the <kbd>y</kbd> and the <kbd>z</kbd> key, only when <kbd>command</kbd> is pressed. This makes using the `Undo` shortcut so much more ergonomic.

## How to use

The keymap was created using [Ukulele](https://software.sil.org/ukelele/) and is supplied as a bundle and as a keymap.

You can either drop the keymap files in `~\Library\Keyboard Layouts` or use Ukulele to do the installation for you via the included organiser.

[TODO] Add reference to Ukulele installation doc.

## FAQ

### Wait. So you are just switching <kbd>y</kbd> and <kbd>z</kbd>?

No, this keyboard layout only switches <kbd>y</kbd> and <kbd>z</kbd> when the <kbd>command</kbd> key is pressed. If not, <kbd>y</kbd> and <kbd>z</kbd> behave according to the german keyboard layout.

### Hm. can't this be solved by just using the System Preferences keyboard shortcuts setting?

No, using System Preferences is not an option. While System Preferences can remap menu options, it needs to know the _exact_ name of the menu option. In case of `Undo` many applications will change the menu option title depending on the current context. E.g. `Undo typing` or `Undo delete 4 items` which makes it almost impossible to completely solve this.

### Why not just use karabiner?

While [karabiner](https://karabiner-elements.pqrs.org/) is awesome, I wanted a solution that would not require any third party applications.
