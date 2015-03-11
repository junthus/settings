# settings for subl

## preference
```
{
    "auto_indent": true,
    "color_scheme": "Packages/User/Monokai (SL).tmTheme",
    "default_encoding": "UTF-8",
    "default_line_ending": "unix",
    "detect_indentation": true,
    "folder_exclude_patterns":
    [
        ".git",
        "node_modules"
    ],
    "font_size": 12,
    "highlight_line": true,
    "ignored_packages":
    [
        "Vintage"
    ],
    "line_numbers": true,
    "match_brackets": true,
    "match_brackets_angle": true,
    "match_brackets_content": true,
    "open_files_in_new_window": false,
    "remember_open_files": true,
    "rulers":
    [
    ],
    "show_tab_close_buttons": false,
    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "trim_automatic_white_space": true,
    "trim_trailing_white_space_on_save": true,
    "use_tab_stops": true,
    "word_wrap": false
}
```

## install package control

ctrl + ` (terminal)

```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```

## linking
* OSX
```
$ ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl
```
* using Homebrew or /usr/local/bin in $PATH
```
$ ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl
```