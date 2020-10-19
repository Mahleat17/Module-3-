# Module-3-
Lab Activity 
#player_actions.py
#10/18/2020
#Mahleat Kidanemariam 

def check_play_again(user_input):
    def check_play_again(y,n):
        yesChoice = ['y']
        noChoice = ['n']
# Convert their input to lowercase.
input = raw_input("Would you like to play again? (y/n) ").lower()
# Check if our answer is right
if input in yesChoice:
    # This is where we input a function or a particular code to continue the play   
elif input in noChoice:
    # This is where we input a function or a specific code to exit the game
    exit 0
else: 
    print "Invalid input.\nExiting."
    exit 1
      #player_actions.py

check_play_again(input("Would you like to play again? Type Y for Yes or N for No: \n"))



#shop.py
#10/18/2020
#Mahleat Kidanemariam 


def check_money(total_cost, customer_money):
    total_cost= calulation()
    if customer_money >= total_cost:
     print ("True")
    elif customer_money <= total_cost:
     print("Dear customer you don't have enough money to purchase the items ")



#This should print False
can_pay = check_money(107, 49)
print(can_pay)

#This should print True
can_pay = check_money(6, 88)
print(can_pay)
