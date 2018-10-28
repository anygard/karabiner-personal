README
======

This is "Complex Modifications" rules for [[Karabiner-Elements][https://pqrs.org/osx/karabiner/]]

Usage
-----

Hopefully this rule can be added to the official rules
[[list][https://pqrs.org/osx/karabiner/complex_modifications/]] otherwise you
will have to insert the contents of the karabiner-anygard.json file into your
karabiner.json [[see][https://pqrs.org/osx/karabiner/json.html]] for
information abut karabiner.json. In short you have to insert the
karabiner-anygard.json content into the rules element.

I have set the "to_if_held_down_threshold_milliseconds" to 20 in order to have
the "Switch from US input source to Swedish while caps lock is held down" rule
work properly.

You can use the "Karabiner-Elements EventViewer" to see what the active input
source is called, it is then trivial to search and replace that name in the
JSON code in order to customize the languages or input sources.
