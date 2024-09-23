# Pokebattle
Pokemon Simulated Battle using Express and Typescript

Submitted by Jene🚍🏎🚉🚅🚇🚃🚋

# <!> Instructions for Running without error <!>            
                                                                
  1. Add this in package.json:                                   
                                                                  
    "scripts": {                                                  
        "prompt-sync": "ts-node scripts/prompt-sync.ts",         
        "start": "ts-node pokebattle.ts && node pokebattle.js",                
        "build": "tsc"                                            
    }                                                             
  **this runs twice but both (.js/.ts)produce the same outcome**
    
  2. Run in terminal: 
    
    npm run start

# <!> Program Navigation <!> 

## Use arrow keyes to navigate through options:

### [PokeBox Select an Option (Use `⬆` and `⬇` arrow keys then press `SPACEBAR` to mark then `ENTER`)]
*   ( ) [1]Store
*   (*) [2]View
*   ( ) [3]Find
*   ( ) [4]>Exit<

 ## `SPACEBAR` to select or de-select
 ##  `Enter` to confirm

* You've selected [2], below is the preview
### Choose some options [2]View 
* Follow the link to the API: http://localhost:8080/PokeBox 
* Then >>>
* Press any key to continue . 
  
  * > Select any link provided then...
  * > Press [any key] to confirm:

. . 

                                                             
 # 🏎Scope and Limiation🏎:
 
## Activity Deliverables:
  
Create endpoints to simulate a face off between two pokemons.
Using pokeapi data, create an endpoint that accepts
  * > 2 parameters (pkmn1 and pkmn2).
   * > using stats.name = "hp" and stats.name = "attack", simulate a battle.
     the pokemon with the highest remaining HP wins.** 
    > If both has the same HP after the battle,
      * > the battle is a draw.
     > when both pokemons fainted,
      * > it is also a draw.
 
> Expected results:
  (test cases)
          ditto vs pikachu
            {
                winner: null, // no winner
                pkm1: {             
                   name: "ditto",
                   attack: 48,
                   attack: 48
                },          
                pkm2: {             
                   name: "pikachu",
                   attack: 35,
                   attack: 55
                },
                results: "draw"
            }
  
 #  Limitations:
 ## * No checking for duplicates
 ## * Must be run with ts-node
 ## * Must Store atleast 1 pokemon before finding ( [3] - Find ) any pokemon in the API

  
