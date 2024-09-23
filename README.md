# Pokebattle
Pokemon Simulated Battle using Express and Typescript

Submitted by Jene🚍🏎🚉🚅🚇🚃🚋

# <!> Instructions for Running without error <!>            
                                                                
  1. Add this in package.json:                                   
                                                                  
    "scripts": {                                                  
        "prompt-sync": "ts-node scripts/prompt-sync.ts",         
        "start": "ts-node pokebox.ts && node pokebox.js",                
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
 
  ## Activity for Typescript:
  
 * ### Create a web api to simulate a pokemon box system. 
    ####  > This will include the following endpoints:
  
   *     1. store pokemon - parameter will be id or name, this will store a pokemon in a list...
     >  - called box (Box.json is utilized)
   *     2. view box - list all pokemon inside your box
   *     3. view pokemon - displays the details of the pokemon (from pokeapi)...
     >   - this will throw an error if pokemon is not on your box
  
 #  Limitations:
 ## * No checking for duplicates
 ## * Must be run with ts-node
 ## * Must Store atleast 1 pokemon before finding ( [3] - Find ) any pokemon in the API

  
