# RUNNING OFFENSE ANALYSIS
How important is the run game to NFL offenses and general team success?
- In essence: **should RBs be paid?**

## TODOs:
- [ ] See correlation between Y/C and passing success (does running ball *really* open up the passing game?)
    - [ ] Correlation between Y/C and passing yards
    - [ ] Y/C and pssr rtg
    - [ ] Y/C and passing Y/A
- [ ] See RBs success as a receiver
    - [ ] View pssr rtgs when targeted between different positions
        * This will likely require RSQL to sort pssr rtgs b/w positions
        * Ex: SELECT median(pssr_rtg) FROM csv WHERE pos = RB \ TE \ WR
            * Is there a way to do this in one query or do we have to create a query for each position
    - [ ] View pssr rtgs when targeted between specific RBs
      * Are star RBs really that much better as receivers than average ones?
      * Consider: Saquon's pssr rtg when targeted is actually pretty bad (at least in years 22/23)
        * Also consider pssr rtg of Giants QBs is not very high anyway
      * Ex: SELECT pssr_rtg FROM csv WHERE pos = RB AND targets > 65 (or any arbitrary number, could be median num of targets)
- [ ] Is there a way to quantify RB's value in dollars?
  * Quantify value RBs add (# of points they score, # of yards they score, how much they contribute
  to win probabilty, etc.) in proprtion to entire salary cap
      * Need to compare value RBs add in relation to what WRs and QBs add
- [ ] Create another draft of ***rushingPaper.pdf***
  