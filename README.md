# HTML-select-option
Gathering more easily stylable replacements for the Select option on an HTML form, because the default one is really annoying!
The aim is to have a few really good, responsive/cross browser/other buzz-words ready select form elements
to be dropped into a web form that needs some styling (so we don't have to fight the default).

---  


|               | Browser support  | Responsive  | min.size | Solution*   |
| ------------- |:----------------:|:-----------:|:--------:|:-----------:|
| CoDrops       | ie9+             | Yes         | ?        | Replacement |
| CoDrops2      | ?                | ?           | ?        | Custom      |
| Select2       | ?                | Yes         | ?        | Replacement |
| cssReset      | ?                | Yes?        | ?        | Original    |

Solution*
* Original: Uses pure CSS to change the default
* Replacement: Creates it's own HTML for ease of styling, usually keeps the original select element for accessibility
* Custom: You have to write/copy original HTML, it doesn't involve the default select


####[CoDrops](http://tympanus.net/Development/SelectInspiration/)
* Super simple for styling (minimal structure)
* Outrageous examples - if you're looking to do some visual wizardry, this could be the one for you
* No dependancies! Works by replacing the original select tag

####[CoDrops2](http://tympanus.net/codrops/2012/10/04/custom-drop-down-list-styling/)
You use a totally custom markup - no select element in play

####[Select2](https://select2.github.io/)
*
* Uses jQuery & replaces the original select tag
