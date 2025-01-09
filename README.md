# xonsh-logo

### The list of images

The xonsh logo, design and pictures are in [5142](https://github.com/xonsh/xonsh/issues/5142) now. Will be here soon.

### iTerm2 icon for xonsh shell

Example:

![image](https://github.com/user-attachments/assets/1ed2cbba-75a7-4394-a908-e8b2cfb2e8c7)

How to change iTerm2 icon:

1. Download [iTerm2-green-xonsh-shell.icns](https://github.com/anki-code/xonsh-logo/blob/main/iTerm2-green-xonsh-shell.icns).
2. [Change icon](https://support.apple.com/en-gb/guide/mac-help/mchlp2313/mac): open `Applications`, open menu for `iTerm2`, click `Get info` and drag and drop `icon.iconset` to iTerm2 icon. Now close iTerm2 and remove it from dock. On next clean iTerm2 start you will see new icon.

How to create your own icon:

1. Copy and change [Figma source file](https://www.figma.com/file/Ncz44QwwaKXTYejbBie8xe0B/iTerm2-icons?node-id=251%3A140) (thanks to [iterm2-icons](https://github.com/jasonlong/iterm2-icons)).
2. Click `Export...` to get zip file with images.
3. Rename the directory with images to `icon.iconset`.
4. Add `icon_` prefix to all files in the directory.
5. On MacOS run `iconutil -c icns icon.iconset` to create `icon.iconset` file.
6. Now you can change the icon.

Note! You can use this icon for any terminal emulator.
