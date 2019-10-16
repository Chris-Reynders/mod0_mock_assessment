`making a sandwich`



**1 prep. Ingredients**
  - 1.1 prep. Plate
    1.1.1 find a clean Plate
    1.1.2 put the Plate on your table
  - 1.2 prep. Bread
    1.2.1 select Bread
      1.2.1.1 white Bread
      1.2.1.2 wheat Bread
      1.2.1.3 wholeGrain Bread
      1.2.1.4 if Bread=False, returns "we have a gluten-free option"
      1.2.1.5 else Next
    1.2.2 toast Bread
      1.2.2.1 remove breadSlice from breadBag
      1.2.2.2 go to Toaster
      1.2.2.3 put breadSlice in Toaster
      1.2.2.4 select toastiness{1-10}
      1.2.2.5 depress toasterLever
      1.2.2.6 wait
    1.2.3 put Bread on Plate      
  - 1.3 prep. Sauce
    1.3.1 select Sauce
      1.3.1.1 ketchup
      1.3.1.2 mustard
      1.3.1.3 jelly
      1.3.1.4 peanutButter
    1.3.2 spreadSauce
      1.3.2.1 if selectSauce returns "peanutButter" AND "jelly"
      1.3.2.2 end spreadSauce && skip to **2 combine.Ingredients**
      1.3.2.3 else Next
  - 1.4 prep. Filling
    1.4.1 select Filling
      1.4.1.1 meat
      1.4.1.2 vegetable
      1.4.1.3 cheese
      1.4.1.4 veganOption
      1.4.1.5 glutenFree (boolean)
        1.4.1.5.1 if glutenFree=True, makeBread=False
    1.4.2 grill Filling (boolean)
      1.4.2.1 if True, returns "good call!"
      1.4.2.2 else returns "are you sure?"
      1.4.2.3 until True
**2 combine.Ingredients**
  - 2.1 stack Ingredients
      2.1.1 put Filling on Bread
        2.1.1.1 if Filling=False endLoop
      2.1.2 put Cheese on Filling
        2.1.2.1 if Cheese=False endLoop
      2.1.3 put Bread2 on Cheese
  - 2.2 press sandwich (optional)
**3 cut.Sandwich**
  - 3.1 diagonally
  - 3.2 else, returns "How barbaric!"
**4 eat.Sandwich**
  - 4.1 "Yum!"
