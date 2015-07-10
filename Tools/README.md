# Tools

> Tools do not make the craftsman.

...but they definitely do make it easier getting the job done.


<br />
## Editor

If you’re developing native iOS or Android code, you’re obviously bound to [Xcode](https://developer.apple.com/xcode/) and [Android Studio](http://developer.android.com/sdk/index.html).

If you’re developing web code, you have many more choices. However, we highly recommend using [Sublime Text](http://www.sublimetext.com/) as it gives us the ability to share configurations and supplemental tools.

### Sublime Text

Before moving on, you must install [Package Control](https://sublime.wbond.net/installation). It supercharges Sublime Text with a package manager.

Once you’ve set up Package Control, you may start installing plugins by hitting `Cmd + Shift + P` to open up the command dialog, and then begin typing “install” until you see “Package Control: Install Package”. Then hit `Return` to find and install the following plugins:

- **BufferScroll**: remembers your open files, scroll position, saved state, and more
- **Case Conversion**: allows you to convert letter-casing of the selected text
- **[DocBlockr](https://github.com/spadgos/sublime-jsdocs)**: simplified and clean commenting
- **EditorConfig**: enables teams to share editor settings such as whitespace, etc
- **Emmet**: simplifies writing HTML using CSS selectors
- **GitGutter**: shows "modified" lines in the sidebar
- **HTMLPrettify**: prettify HTML, CSS, and JSON
- **Pretty JSON** (if HTMLPrettify doesn't work): prettify JSON
- **Inc-Dec-Value**: increase and decrease values such as pixels, %, hex, etc using the keyboard
- **Sass**: enables syntax highlighting for Sass
- **SCSS**: enables syntax highlighting for Sass in the SCSS flavor
- **SideBarEnhancements**: adds a whole bunch of useful sidebar/file utilities
- **Sublime Alignment**: align your variable/property declarations so your code is more readable
- **SyncedSideBar**: highlights the active file

To install all of these plugins (and some more), use th *Sublime Packages.zip* file and merge it with `Sublime Text.app -> Show Package Contents -> Contents -> MacOS -> Packages`.

You can also spill some paint onto Sublime’s default theme. Some recommendations are:

- **Predawn** \*
- **Spacegray**
- **Material Theme**

_\* If you choose to go with Predawn, make sure to copy the `sidebar_medium` and `tabs_medium` options as mentioned below._

To customize Sublime’s behaviors to our specific practices, we use the following configuration (hit `Cmd + ,` to open your preferences):

```json
{
    "bold_folder_labels": true,
    "caret_extra_width": 1,
    "caret_style": "wide",
    "color_scheme": "Packages/User/predawn (SL).tmTheme",
    "drag_text": false,
    "fade_fold_buttons": false,
    "find_selected_text": true,
    "font_size": 16,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "Vintage"
    ],
    "rulers":
    [
        120,
        80
    ],
    "scroll_past_end": true,
    "sidebar_medium": true,
    "tabs_medium": true,
    "theme": "predawn.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "word_wrap": false
}
```


<br />
## Version Control

Evidently, our VCS of choice is [Git](http://git-scm.com/) and our source code is hosted by [Github](http://github.com/). We use some tools to make the Git Life easier:

### [Tower](http://www.git-tower.com/)

Tower is an awesome Git GUI with a pleasant design and great features like stashes, keyboard shortcuts, automatic fetches, and lots more.

### [Kaleidoscope](http://www.kaleidoscopeapp.com/)

Merging conflicts suck - and it’s where a lot of bugs come from. Kaleidoscope provides a simple UI that easily integrates into Tower and makes merging conflicts less of a pain.


<br />
## Productivity

### [ClipMenu](http://www.clipmenu.com/)

ClipMenu is a utility app that keeps a history of your clipboard. Verrrry useful for us developers.

**Note**: there’s a conflict between the app’s default shortcuts and some default Mac shortcuts. So, once downloaded, carry out these steps:

1. Open ClipMenu
2. Open Preferences
3. Switch to the Shortcuts tab
4. Change “Main Menu” to `Cmd + Opt + v`
5. Change “History Menu” to `Cmd + Opt + g`
6. Change “Snippets Menu” to `Cmd + Opt + b`

### [Better Touch Tool](http://bettertouchtool.en.softonic.com/mac)

Better Touch Tool is a utility app that let’s you add keyboard shortcuts to a lot of basic MacOS actions, like window sizing/moving. [Here’s a quick tutorial](http://mac.appstorm.net/reviews/productivity-review/controlling-your-mac-with-bettertouchtool/) to get you familiarized.





## Database


### [Navicat](http://www.navicat.com/download)

SQL GUI.

## Docker

### [Kitematic](https://kitematic.com/)

Mac App for Docker