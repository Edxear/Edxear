from random import randint

choice = ["piedra","papel","tijera"]
def main():
    computer = choice[randint(0,2)]

    print("Bienvenido al juego piedra, papel y tijera\n")
    player = input("Tú elección: ").lower()
   
    print("computer Chose: " + computer)

    if player == computer:
        print("Draw")
    elif player == "piedra" and computer == "papel":
        print("Computer Wins")
    elif player == "piedra" and computer == "tijera":
        print("Player Wins")
    elif player == "papel" and computer == "piedra":
        print("Player Wins")
    elif player == "papel" and computer == "tijera":
        print("Computer Wins")
    elif player == "tijera" and computer == "piedra":
        print("Computer Wins")
    elif player == "tijera" and computer == "papel":
        print("Player Wins")
    main()

main()
