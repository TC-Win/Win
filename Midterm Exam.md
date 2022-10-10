Start 
SEND "Pls enter the temperature" TO DISPLAY
IF temperature < 18 c?
SEND "Cold, the perfect temperature for sleep is 18-21 degrees"
  Else temperature > 21 c?
  IF SEND "Perfect" TO DISPLAY
    Else SEND "No!, the perfect temperature for sleep is 18-21 degrees."TO DISPLAY
End 
