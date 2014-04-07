tintin-modules
==============

          DISCWORLD MUD Modules for the Tintin++ Mudclient


This is a collection of small modules, all independent from each other, and tailored for specific guilds.

CURRENT MODULES:
---------------

For caster classes (Wizards, Witches)
   
    Enchantment Levels
          Displays the current enchantment level of an item in the form of a progress bar.
   
    Delusion Stages
          Displays a progress bar, indicating at which stage of the pampering process the item is at the moment.
          It does not represent in any way the time it will take for the item to complete the process and "turn".

    Unseen University Library SpeedWalks
          A set of aliased speedwalks to help you reach some of the most frequently visited spots within the Library.
          Use with care. There's always a risk of ending up in L-Space whenever you move through a magical library.
          You can type 'uul' for usage instructions and a list of destinations.

For priests

    Holy Auras
          Substitutes the "flavour" line in amulets, holy symbols, relics and prayer books for a simpler, 
          coloured one which simply states the name of the god to whom the item has been consecrated.

    Faith Rod Charges
          Displays a progress bar per faith rod part, indicating the ritual, if any, that it contains, and the
          degree to which it has been charged.

    Prayer Beads Charges
          Displays a progress bar for a set of prayer beads, depicting the stage to which it has been charged
          and a rough approximation of the holy items it can replace at the time.

For everyone

    Condition Levels
          This module changes the text description of an item's condition for a clearer (I hope) progress bar.

    Info Bar
          This adds a status bar at the top of your tintin++ screen, showing stuff such as the current date and time,
          session name and character name, terminal dimensions, a countdown until you idle-out of the MUD, and the
          usual stuff (HP, GP, XP, Burden and combat attitudes).
          In order to make it work, you'll need to load the module and type 'ttm-prompt' to initialise your prompt and hit point monitor.

    Moon Dragon
          We all know those adorable little munchkins can be a bit spammy at times.
          This module aims to make their antics a bit less intrusive by dimming them.

CONSIDERATIONS:
   - If the current terminal width is too small, the progress bars will not appear at all. Depending on the module, you may need a terminal width in excess of 160 columns.

If you should find any bugs, or if you have any doubts or ideas regarding any of my modules, please feel free to contact me in the game.

New grinnily.
