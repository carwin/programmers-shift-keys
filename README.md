# Programmer's Shift Keys

Programmer's Shift Keys takes your `Shift` keys, which are useless when pressed by
themselves, and makes them great by turning individual strokes into: `()`, `[]`, or
`{}`!

The original idea for this came from an
[article](http://stevelosh.com/blog/2012/10/a-modern-space-cadet/) by Steve Losh
where he remapped his `Shift` keys to `()`. I've expanded on this idea by pairing
modifier keys with `Shift` to give `[]` and `{}`.

This project aims to make this available for multiple operating systems and,
ideally, will someday come with some way to install and configure Programmer's
Shift Keys. Until then, read the instructions in this file for your particular
situation.

## OSX

#### Requirements
 - [Karabiner](https://pqrs.org/osx/karabiner/)

#### Installation

After installing Karabiner, the process for using Programmer's shift keys is
relatively easy.

 1. Open the KarabinerPreferences application.
 2. Click the **Misc & Uninstall** pane.
 3. Click the button **Open private.xml**. This will open the file's location in
    Finder.
 4. If you are already using custom settings in `private.xml`, copy the `<item>`
    blocks of the layout you're using into the file. Otherwise, you can simply
    replace the entire file's contents with one of the layout files in this
    repository.
 5. Save the file.
 6. Back in KarabinerPreferences, go back to the first pane, **Change Key**, and
    click **Reload XML**.
 7. At the top of the list you should now see **Programmer's Shift Keys**.
    Expand that list and enable the features you'd like to use.


