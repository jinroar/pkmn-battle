# Pokebattle
Pokemon Simulated Battle using Express and Typescript

Submitted by Jene🚍🏎🚉🚅🚇🚃🚋

# <!> Instructions for Running without error <!>            
                                                                
  1. Add this in package.json:                                   
                                                                  
    "scripts": {                                                  
       "start": "ts-node pokebattle.ts && node pokebattle.js",
       "build": "tsc"                                
    }                                                             
  **this runs twice but both (.js/.ts)produce the same outcome**

    "scripts": {                                                  
        "battle": "ts-node pokebattle.ts",                               
    }   
    
 **this runs the .ts program**



    
  2. Run in terminal: 
    
    npm run battle
    npm run start

# <!> Program Navigation <!> 

### [PokeBox Select an Option (Use `⬆` and `⬇` arrow keys then press `SPACEBAR` to mark then `ENTER`)]



                                                             
 # 🏎Scope and Limiation🏎:
 
## Activity Deliverables:
  
Create endpoints to simulate a face off between two pokemons.
Using pokeapi data, create an endpoint that accepts
* 2 parameters (pkmn1 and pkmn2).
  * using:
     >   stats.name = "hp" and
     >>  stats.name = "attack",
     >>>   simulate a battle.
   * **the pokemon with the highest remaining HP wins.**
  *  If both has the same HP after the battle,
      * > the battle is a draw.
   * when both pokemons fainted,
     * > it is also a draw.
 
## Expected results:
(test cases)
 > ditto vs pikachu
  >>{
     winner: null, // no winner
>>>pkm1: {             
         name: "ditto",
           attack: 48,
        attack: 48
          },          
>>>pkm2: {             
      name: "pikachu",
   attack: 35,
       attack: 55
         },

>  >>>>>results: "draw"
          >>}
  
 #  Limitations:
 ### * Must be run with ts-node
 ### * Wrong input of pokemon will cause the program to force exit on some cases
