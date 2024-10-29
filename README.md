PyPassword Generator
Welcome to the PyPassword Generator! This is a simple Python script that generates a custom password based on the user’s preferred mix of letters, numbers, and symbols.

How to Use:
Run the Script:

Start the program by running the script in a Python environment.
Specify Your Preferences:

The program will prompt you to enter the number of each character type you want in your password:
Letters: Choose how many alphabetic characters (uppercase and lowercase) you'd like.
Symbols: Enter the desired number of special characters (e.g., !, #, $).
Numbers: Specify the number of numeric characters (e.g., 0-9).
Get Your Password:

The program will generate a random password using your specifications.
The result will be a strong, shuffled password containing your chosen combination of letters, symbols, and numbers.

How It Works:
The program uses Python's random.choice() function to randomly select characters from lists of letters, numbers, and symbols.
Shuffling: Each time a character is added, the random.shuffle() function shuffles the password to enhance randomness.
The final password is displayed to the user, ensuring a secure mix of letters, symbols, and numbers in a randomized order.