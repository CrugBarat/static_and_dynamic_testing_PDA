### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby

class CardGame


  def checkforAce(card) # self.check_for_ace(card)
    if card.value = 1  # == 14
      return true
    else
      return false
    end
  end

  dif highest_card(card1 card2)    # def self.highest_card(card1, card2)
    if card1.value > card2.value                                
       return card  # card1
     else                          
       return card2                
     end                           
   end                             
 end    # remove end

def self.cards_total(cards)
  total   # total = 0
  for card in cards
    total += card.value
    return "You have a total of" + total  # missing space at end of string, total.to_s
  end # insert above line 31
end

# end
```
