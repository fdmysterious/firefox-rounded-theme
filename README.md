Firefox rounded theme with auto-hiding tree-style tabs
======================================================

Mixed from:
- https://www.reddit.com/r/FirefoxCSS/comments/114wtj9/roundedfox_a_css_configuration_for_minimalists/
- https://www.reddit.com/r/FirefoxCSS/comments/uldl0q/a_minimal_ui_w_autohiding_tree_style_tabs/

![Theme preview](firefox-tabs-rounded.png)

Configuration
-------------

1. Go to `about:config`, and enable `toolkit.legacyUserProfileCustomizations.stylesheets`;
2. Install the [Tree-Style-Tabs](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/) extension
3. Go to the extension configuration. Configure `Appearance -> Ident level` to `0`, and make sure the used theme is `Proton`
4. In the extension's preferences, in `Avanced -> Extra style rules for sidebar contents`, load the `tst.css` file contents
5. Now, go to `about:profiles`. Find the currently used profile folder.
6. In this folder, create a `chrome` folder. In this folder, paste the `userChrome.css` file.
7. Restart firefox. You should be good to go! :dancer:

There are also interesting tweaks on this page: https://github.com/piroor/treestyletab/wiki/Code-snippets-for-custom-style-rules#full-auto-showhide-theme
