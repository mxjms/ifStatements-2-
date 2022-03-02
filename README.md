# ifStatements-2-

userReply = input("Do you need to ship the package? (Enter yes or no)")

if userReply == "yes":
    print("We can help you ship that package!")
else:
    print("Then get out of my store.")

print()

userReply = input("Would you like to buy stamps, buy an envelope, or make a copy? (Enter stamps, envelope, or copy) ")
if userReply == "Stamps":
    print("We have many stamp designs to choose from.")
elif userReply == "Envelope":
    print("We have many envelope sizes to choose from.")
elif userReply == "opy":
    copies = input("How many copies would you like? (Enter a number) ")
    print("Here are {} copies.".format(copies))
else:
    print("Thank you, please come again.")
