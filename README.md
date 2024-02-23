# ABtest_Experiments_Netflix
(Academic task)

![image](https://github.com/DAVIDRE1/ABtest_Experiments_Netflix/assets/138836619/22917d65-5a1a-4055-8326-42fbeb169fab)

Goal: Optimize Netflix browsing time

Data: Simulated from  https://nathaniel-t-stevens.shinyapps.io/Netflix_Simulator_v4/

• Tile Size: The ratio of a tile’s height to the overall screen height. Note the tile’s aspect ratio is fixed
so changing this factor changes the size of the tile, but not its shape. Smaller values correspond to a
larger number of tiles visible on the screen, and larger values correspond to fewer visible tiles.        
• Match Score: A prediction of how much you will enjoy watching the show or movie, based on your
viewing history. This is recorded as a percentage, with larger values indicating a higher likelihood of
enjoyment.         
• Preview Length: The duration (in seconds) of a show or movie’s preview.         
• Preview Type: The type of preview that is autoplayed.         

Region of operability for each of these factors:        
     Factor Code Name Region of Operability       
     Tile Size Tile.Size [0.1,0.5] default: 0.2         
     Match Score Match.Score [0,100] default: 95       
     Preview Length Prev.Length [30, 120] default: 75          
     Preview Type Prev.Type {TT, AC} default: TT        


What I used: Iterative experimentation process using Statsmodels, Pandas, NumPy and Matplotlib

Performed by:
    Sonal Shad       
    Cassie Richter       
    Inseong Han      
    David Ramirez        
