# pyPokedex
Lil Tool I made for making my Pokemon fan game. Re-upload from my old github

DEV: Gray
GITHUB: grayed-out
Start: 06/17/2022
Re-Upload / Revisions Starting: 02/13/2023

Proj: Pokedex ++

Currently made to be very human redable, planning on making an alt version 
that is more friendly to be searched thru with automation

Use Case:
    Used to grab and save specified information about a given pokemon
    Relies on pokeAPI
    I made this for getting pokemon data for fast imports to a game I am working on
    However I feel others might get a use from it so it will inevitably be released to the public
    
How to:
    Run the Main.py file
    enter either the name or national dex number of the pokemon in the text field
    hit search
    (optional) Save displayed info and sprites by pressing the save button at the bottom
    
Functionality:
    Retrieves the following information on a pokemon
    - Name                - Base Stats
    - Dex #               - Abilities
    - Typing              - Shiny and Non-Shiny Sprites
    - Learnable Moves
    
    from there the displayed info can be saved into the following format in
    
    |-main.py
    |-res
    |-pokemon (here is where it will be stored)
      |- [PokemonName]Line1
      |   |-[Evo1]
      |   |-[Evo2]
      |   |-[Evo3]
      |       |- [Evo3].txt (contains stats, moves, abilites, etc...)
      |       |- [Evo3]_back.png
      |       |- [Evo3]_front.png
      |       |- [Evo3]_shiny_back.png
      |       |- [Evo3]_shiny_front.png
      |
      |- [PokemonName]Line2
     
     
     
Misc:
    This is my first python program lets goooo
