## 1.6.8
Fixed bug where end tag was being displayed on fold instead of start tag.

## 1.6.7
Foldable regions no longer require a space, so "//#region" now works.

## 1.6.6
Fixed keyboard shortcuts listed in README.md.

## 1.6.5
For some syntaxes, such as Babel ES6, the leading whitespace was being underlined. This should now be fixed.

## 1.6.4
Added a sleep to fix the 'fold on load' option no longer working with the latest version of Atom. Just a temporary solution until I can figure out the proper way of knowing when it's safe to fold regions.

## 1.6.3
Updated the descriptions for the settings. Updated README.md and CHANGELOG.md (to reflect that the last version was acutally 1.6.0 and not 1.5.3).

## 1.6.0
Removed the need to add comment characters in the settings for the beginning and end of foldable regions.
Added code to retrieve current grammars comment style to allow for language agnostic region comments.
Added .text selector to stylesheet to enable colorization on html files.

## 1.5.2
Find-in-Files works again when 'auto fold on file load' is enabled. Yeah, that was a bad bug.

## 1.5.1
Updated README.md.

## 1.5.0
Added a setting to automatically fold a file on load. Defaults to false.

## 1.3.1
Updated README.md with screenshot.
Added author's name to LICENSE.md.

## 1.3.0
Added optional flag for experimental highlighting of folding tags. Folded tags use the @text-color-info color.
Added tags to project.
