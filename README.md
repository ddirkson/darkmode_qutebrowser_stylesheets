# darkmode_qutebrowser_stylesheets
Two versions:
  * darkmode stylesheet - finer grained definitions for what to darken and how to do so
  * draconian darkmode stylesheet - lots of '!important' flags, solid darkmode coverage for pages but harder to customize

Can add a keybinding in qutebrowser like this: 
`:bind ,n config-cycle content.user_stylesheets ~\\qutebrowser_stylesheets\\darkmode-stylesheet.css ""`
to toggle between light and darkmode. 
