https-everywhere-yorkuni
========================

University of York Ruleset for EFF HTTPS Everywhere extension (https://www.eff.org/https-everywhere)

Installation
============

Firefox
-------

Refer to https://www.eff.org/https-everywhere/rulesets

Google Chrome
-------------
[Based on instructions from http://pastebin.com/cFNzUmiZ]

(Windows)

1) In your OS, go to the folder where the HTTPS Everywhere extension was installed. On Windows, that's
  %USERPROFILE%\AppData\Local\Google\Chrome\User Data\Default\Extensions\gcbommkclmclpchllfjekcdonpmejbdp\VERSION
  (replace VERSION, of course).
  
2) Put the XML file(s) in the rules subfolder.

3) Edit rule_list.js to include the newfile in the array (eg: var rule_list = ["rules/default.rulesets","rules/york.ruleset.xml",];)

4) Restart Chrome.
