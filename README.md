# SeoeCs
A smart character sheet app for Edge of the Empire campaigns

Phase One:
  Read a character sheet (It's a JSON! Whoop)
  Populate the in-app character object with the relevant stats
  Display the character information
  

Phase Two:
  Dice roller - 
    User selects how many green/yellow/blue/force die to roll.
    Generate results based on the selection
    Display generated results
    
Phase Three:
  Inventory -
    A set of dynamic lists which store information about the character's belongings.
    Can be added/removed to/from at will.
    
Phase Four:
  Character aware dice roller -
    User chooses one of the skills/abilities from their character sheet
    (?) User can add boost die at behest of GM
    Application decides how many of each dice is necessary for that roll
    Application generates the results of the roll for that stat
    Display generated results

Phase Five:
  XP Logger -
    User inputs a starting XP amount.
    User adds to an XP Log:
      - Each log contains:
        - The change to XP (amount and +/-)
        - A small message describing the source of the change
    Logger can also be viewed with filters so sources of loss/gain can be isolated for better UX

