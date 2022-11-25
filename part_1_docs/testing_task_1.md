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
    if card.value = 1: # Card.value = 1 is an error this should be a double equal for comparison
      return True
    else # The colon(:) is missing after the else statment
      return False


  dif highest_card(self, card1 card2): # Spelling error in function definition should be 'def' Also missing comma between card1 and card2
  if card1.value > card2.value: #If statement not indented properly, it should be tabbed to the right aalong with any corresponding lines that follow the if
    return card # card is not defined, this should be changed to card1
  else:
    return card2



def cards_total(self, cards):
  total #total has not been assigned a starting value
  for card in cards:
    total += card.value
    return "You have a total of" + total # This will return a TypeError you can't concatonate a string and an integer and the return statement should also be indented to the left outside of the for loop so that it it returns the total once all iterations of the loop have been completed.

```
