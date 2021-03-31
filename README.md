# Write-a-GAME-Code-to-find-the-treasure-Island.
Mission is to find the Treasure

print('''


*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_______]
*******************************************************************************
''')
print("Welcome to the Treasure Island.\n\n")
print("Your mission is to find the Treasure.\n\n ")
choice1 = input('You are at the crossroad where do you want to go? type "left" or "right".  :').lower()

if choice1 == "left":
    choice2 = input('You have come to a lake. There is an island in the middle of the lake. Type "wait" to wait for a boat.Type "swim" to swim across : ').lower()
    if choice2 == "wait":
        choice3 = input("You are arrived at the island unharmed. There is a huse with a 3 doors One red,one yellow, one blue. Which colour do you want to choose? ").lower()
        if choice3 == "red":
            print("room full of fire")
        elif choice3 == "yellow":
            print("you found the treasure YOU WIN ! ")
        elif choice3 =="blue":
            print("you enter the room in DANGER. GAME OVER")
    else:
            print("You choose the door doesn't exist. GAME OVER.")
else:
    print("you got attacked by an engry trout. Game Over")
