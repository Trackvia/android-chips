# TrackVia Android Chips Edit Text #
This repo is a fork form KLinker41's repository: https://github.com/klinker41/android-chips

We wanted to make changes to the behvaior of the chips library that better met the needs of our users. These changes are:
* Using spaces as delimiters when typing out email addresses. The base implementation only uses commas.
* Not showing all contacts when two characters are typed in that don't match anything. If any number of characters don't match any of the user's contacts, we don't want to show any results.
