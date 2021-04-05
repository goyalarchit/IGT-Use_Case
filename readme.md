# Input File Format
    
    #Line 1 : Recognised Players from each academy separated by commas (sum of these should be l)
    #Line 2 to 2+n-1 : Type Set for each academic representative separated by commas, total n in number
## Sample Input File
    1,1,2
    7,8,6,5,0,0,0
    7,8,6,5,0,0,0
    6,6,8,7,0,0,0

# How To Run
    ```usage : python3 useCase.py<input_file> <a> <b> <M> <MAF>```
    where
    - a,b : arbitrary constant used in Social Choice Function
    - M : Maximum Possible Fund Allocation Points used in Social Choice Function for Recognised players
    - MAF : maximum possible Reward Funds (Used In social Choice Function) for Representatives