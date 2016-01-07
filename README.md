# AtomJ: Mac OSX IntelliJ keymap for Atom editor
After using IntelliJ and it's keybindings for years it is hard to switch to an editor with a new set of keybindings.

**Meet**: [IntelliJ keybindings](https://www.jetbrains.com/idea/docs/IntelliJIDEA_ReferenceCard_Mac.pdf) combined with [Pivotal's additions](https://github.com/Pivotal-Boulder/IDE-Preferences) for the [Atom](https://atom.io/) editor.

You can read more about Atom keymaps [here](https://atom.io/docs/v0.60.0/advanced/keymaps).

# Usage

In order to use the keymap from this repo it needs to be in your `.atom` folder in your home directory.
You can use the commands below to achieve this, you might have to remove the `keymap.cson` from your `.atom` directory before doing so.
```
git clone git@github.com:geapi/atomJ.git
ln -s [path-to-atomJ-repo]/keymap.cson ~/.atom/keymap.cson
```

# Additional packages
You could install some additional packages to improve your coding experience:
  * [atom-ternjs](https://atom.io/packages/atom-ternjs)
  * [complete-statement](https://atom.io/packages/complete-statement)
  * [git-plus](https://github.com/akonwi/git-plus)
  * [atom-beautify](https://atom.io/packages/atom-beautify)
  * [clipboard-history](https://github.com/unDemian/clipboard-history)
  * [goto-last-edit](https://github.com/plrenaudin/goto-last-edit)

# License
AtomJ is released under the [MIT License](http://www.opensource.org/licenses/MIT).
