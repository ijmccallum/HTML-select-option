# HTML-select-option

The aim is to have a few really good, responsive/cross browser/other buzz-words ready select form elements to be dropped into a web form that needs some styling (so we don't have to fight the default).  

Have a skim thruogh [this css-tricks article](http://css-tricks.com/dropdown-default-styling/) before going down the route of styling a dropdown (or other form elements for that matter).  If you can avoid it and just use the defaults - do!

---  


|               | Responsive  | min.size | Solution*   |
| ------------- |:-----------:|:--------:|:-----------:|
| Default       | Yes         | 0        | n/a         |
| Select2       | Yes         | ?        | Replacement |
| Selectize     | Yes         | ?        | Replacement |
| CoDrops       | Yes         | ?        | Replacement |
| CoDrops2      | ?           | ?        | Custom      |
| cssReset      | Yes?        | ?        | Original    |

Solution*
* Original: Uses pure CSS to change the default
* Replacement: Creates it's own HTML for ease of styling, usually keeps the original select element for accessibility
* Custom: You have to write/copy original HTML, it doesn't involve the default select  


---
####Desktop Browser support by [market share](http://www.netmarketshare.com/browser-market-share.aspx?qprid=2&qpcustomd=0)

|               | IE11     | IE8      | Chrome(40) | IE9      | FireFox(34) |
| ------------- |:--------:|:--------:|:----------:|:--------:|:-----------:|
| Default       | Yes      | Yes      | Yes        | Yes      | Yes         |
| Select2       | Yes      | Yes      | Yes        | Yes      | Yes         |
| Selectize     |          |          |            |          |             |
| CoDrops       | Yes      | NO       | Yes        | Yes      | Yes         |
| CoDrops2      | Yes      | NO       | Yes        | Yes      | Yes         |
| cssReset      |          |          |            |          |             |

So, if you're thinking of supporting all those folks still running on Windows XP
(and therefore stuck with ie8), you're looking at Select2!  

####Mobile Browser support by [market share](http://www.netmarketshare.com/browser-market-share.aspx?qprid=0&qpcustomd=1)

|               | Safari   | Chrome   | Android    | Opera mini  |
| ------------- |:--------:|:--------:|:----------:|:-----------:|
| Default       |          |          |            |             |
| Select2       |          |          |            |             |
| Selectize     |          |          |            |             |
| CoDrops       |          |          |            |             |
| CoDrops2      |          |          |            |             |
| cssReset      |          |          |            |             |





####Default
* It just works

####[Select2](https://select2.github.io/)
* Adds a lot of functionality: search!
* Uses jQuery & replaces the original select tag

####[Selectize](https://github.com/brianreavis/selectize.js)


####[CoDrops](http://tympanus.net/Development/SelectInspiration/)
* Super simple for styling (minimal structure)
* Outrageous examples - if you're looking to do some visual wizardry, this could be the one for you
* No dependancies! Works by replacing the original select tag

####[CoDrops2](http://tympanus.net/codrops/2012/10/04/custom-drop-down-list-styling/)
You use a totally custom markup - no select element in play
