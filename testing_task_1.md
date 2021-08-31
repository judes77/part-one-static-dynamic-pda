### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1:              # should be double equals       
      return True
    else                            # need a colon after else            
      return False
   
                        # there needs to be a comma after card1
  dif highest_card(self, card1 card2): # should be def to define the function
  if card1.value > card2.value:         #  missing indent before if
      return card  # needs to be card1 not card                        
    else:                                 # missing indent before else
    return card2
  
        # there needs to be a comma 
def cards_total(self, cards): # needs an indentation before def
  total                       # the variable total has no value
  for card in cards:          # total shouldn't be here 
    total += card.value       # for will now need indented
    return "You have a total of" + total  
              # total should be concatenated into the string
              # the return should be unindented to be in line with for
```
