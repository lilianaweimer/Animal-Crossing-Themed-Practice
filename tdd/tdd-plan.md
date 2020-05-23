# TDD Plan

Planned features and additions for this problem set.

## General modifications: 
- Add:
    - `art`
    - `town`
    - `player`
        - the `player` class should do things that interact with the other classes, like in the real game!
- Build test suites based on plans below
    - While testing, build out classes for practice and to make sure they're working
    - Then eventually delete them and try the whole thing again! For practice!

## Individual Test/Class Plans: 

### `bugs`
- should have a name (string)
- should have a habitat (string)
- should have a sell price (integer)
- should have a date range of availability (object)
- should have rain availability (Boolean)
- should have an in museum property (Boolean)
- should be able to calculate Flick/CJ price (increase price by 50%) 
- should be able to calculate drop-off box price (decrease by 20%)
- should be able to be added to museum (change Boolean)

### `fish`
- should have a name (string)
- should have a habitat (string)
- should have a sell price (integer)
- should have a date range of availability (object)
- should have rain availability (Boolean)
- should have an in museum property (Boolean)
- should be able to calculate Flick/CJ price (increase price by 50%) 
- should be able to calculate drop-off box price (decrease by 20%)
- should be able to be added to museum (change Boolean)


### `flowers`
- should have a species (string)
- should have a color (string)
- should have a blooming property (Boolean)
- should be able to be watered (Boolean)
- should be able to cross-pollinate (not sure what this should do)
- should not be able to cross-pollinate if NOT blooming or watered

### `fossils`
- should have an assessed property (default false)
- should have a species (string)
- should have a type (multiple or not)
- should have a parts property (default false, if multiple, an array of parts)
- should have an in museum property (Boolean)
- should be able to be assessed (change Boolean)
- should be able to be added to museum (change Boolean)


### `furniture`
- should have a set
- should have a type
- TO CONSIDER: should this refer to an individual furniture item or a furniture set?

### `npcs`
- should have a name (string)
- should have a species (string)
- should have an occupation (string)


### `tools`
- should have a type (string)
- should have a broken property (Boolean, default false)
- should be able to break after a certain number of uses


### `villagers`
- should have a name (string)
- should have a species (string)
- should have a personality (string)
- should have a catchphrase (string)
- should have a lives in town property (Boolean)
- should have a bday (date?)
- should have a gender (string)
- should have a favorite style (string)
- should have favorite colors (array)
- should be able to say their catchphrase (return catchphrase)
- should be able to move in or out (change Boolean)
- should be annoyed if talked to more than 3 times depending on personality (return something other than catchphrase)
