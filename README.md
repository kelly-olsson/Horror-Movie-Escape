#Horror Movie Escape
######[Kelly Olsson](https://github.com/kelly-olsson) & [Hannah Kuo](https://github.com/hannah-kuo)
Horror Movie Escape is a text-based simple dungeon crawler with a real-time synchronized map and ASCII art features.

##Installation 
Import PrettyTable from the prettytable library

```bash
python -m pip install -U prettytable
```
More information [here](https://pypi.org/project/prettytable/)

##Python Features Used

|                Features Used                         |  Location (line number) |
|---------------------------------------------------------|-------------------------|
|  Tuple                                                  |  1501             
|  List                                                   |  566
|  Dictionary or list comprehension                       |  643
|  Selection using the if-statement                       |  588, 594
|  A clever use of repetition with the for or while loop  |  861      
|  Membership operator (in) where it makes sense          |  643 
|  Range function                                         |  643     
|  itertools function(s)                                  |  784     
|  Enumerate                                              |  844  
|  Filter or map function                                 |  760     
|  Random module                                          |  986                


## Game Design

### General Attack Stats

| Attack type |  Chance of Hit | Critical Hit Chance |
|---|---|---|
| Heavy | 40% | 80% (double damage)              
| Medium | 70% | 0%  
| Light | 100%| 80% (double damage)  


### Class Specific Strengths

| |  Shrieking Stumbler | School Jock | Computer Nerd | The Natural |
|---|---|---|---|---|
| HP| 30| 40    | 30 | 30   
| Special Attack | Re-roll 1X for missed attack | +10 HP buff | Light attack 100& critical hit| Heavy attack 60% hit chance 


### Levels and Damages (DMG)

| Leveling Damage |  Level 1 | Level 2 | Level 3 |
|---|---|---|---|
| HP (Jock +10) | 30 | 40 | 50              
| Light Attack (DMG) | 6 | 16 | 26   
| Medium Attack (DMG) | 10 | 20 | 30    
| Heavy Attack (DMG) | 15 | 25 | 35
