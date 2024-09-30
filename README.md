
# **Python Games Collection**

## **Introduction**
Welcome to the Lab 2 of Day 3, where you'll be working on a collection of seven interactive Python games. This project aims to help you practice fundamental programming concepts while having fun. The games include number-based games, string manipulation, and logical thinking puzzles.

## **Games Included**
This project contains the following seven games:
1. **Odd or Even**
2. **Sum and Average Calculator**
3. **Multiplication Table Generator**
4. **Fibonacci Sequence Generator**
5. **Number Guessing**
6. **String Case Converter**
7. **Palindrome String Check**

Each game is accessible through a menu-based interface, allowing users to select and play the games of their choice.

## **Prerequisites**
To run these games, you need to have Python 3 installed on your system. If you don't have it installed, you can download it from [here](https://www.python.org/downloads/).

## **How to Run the Games**
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-username/python-games-collection.git
   ```
2. Navigate to the project directory.
   ```bash
   cd python-games-collection
   ```
3. Run the `main.py` file.
   ```bash
   python main.py
   ```
4. A menu will be displayed with options for each game. Enter a number (1-7) to select a game, or `0` to exit.

## **Game Instructions**

### 1. **Odd or Even**
The program will prompt you to enter a number. It will then check whether the number is odd or even and display the result.

- **Input**: Any integer.
- **Output**: A message indicating if the number is "Odd" or "Even".
- **Exit**: Type `000` to exit this game and return to the main menu.

### 2. **Sum and Average Calculator**
This game allows you to enter multiple numbers. It will calculate and display the sum and average of the entered numbers.

- **Input**: A series of numbers.
- **Output**: The total sum and average.
- **Exit**: Enter any non-number character to end the game.

### 3. **Multiplication Table Generator**
This game prompts you to enter two numbers, a start, and an end number. It then generates and prints multiplication tables for numbers within this range.

- **Input**: Start and end numbers.
- **Output**: Multiplication tables for numbers within the range.
- **Exit**: Enter `0` to return to the main menu.

### 4. **Fibonacci Sequence Generator**
The program will ask you to enter a number. It will then generate and display the Fibonacci sequence up to the entered number.

- **Input**: A single number.
- **Output**: Fibonacci sequence up to the entered number.
- **Exit**: Enter any non-number character to exit the game.

### 5. **Number Guessing Game**
In this game, you set a range (lower and upper bounds) for numbers. The program will try to guess your number using your hints ("greater", "smaller", or "equal").

- **Input**: Range and hints for the program.
- **Output**: The guessed number.
- **Exit**: Enter `quit` to exit this game.

### 6. **String Case Converter**
Enter a string, and the program will give you three options: convert the string to uppercase, lowercase, or title case.

- **Input**: A string and a case conversion option.
- **Output**: The converted string in the selected case.
- **Exit**: Enter `0` to return to the main menu.

### 7. **Palindrome String Check**
The program prompts you to enter a string. It then checks if the entered string is a palindrome (reads the same backward and forward) and displays the result.

- **Input**: A string.
- **Output**: A message indicating if the string is a palindrome.
- **Exit**: Enter `000` to return to the main menu.

## **Code Structure**
The project consists of a `main.py` file, which contains the code for the menu and game logic. Each game is implemented as a separate function within the same file for simplicity. This approach allows easy navigation and modification of each game function.

## **Example Code Snippet**
Here’s a quick example of how one of the games (Odd or Even) is implemented in Python:

```python
def odd_or_even():
    while True:
        user_input = input("Enter a number to check if it's Odd or Even (or type '000' to exit): ")
        if user_input == '000':
            break
        try:
            number = int(user_input)
            if number % 2 == 0:
                print(f"{number} is Even.")
            else:
                print(f"{number} is Odd.")
        except ValueError:
            print("Invalid input! Please enter a number.")
```

## **Usage**
1. **Running the Game**:
   - Open a terminal and navigate to the project folder.
   - Run the following command:
     ```bash
     python main.py
     ```
   - Follow the prompts on the screen to interact with each game.

2. **Game Menu**:
   - After each game ends, you will be returned to the main menu.
   - Press `0` to exit the program.

## **Contributing**
Contributions are welcome! Feel free to open an issue or submit a pull request with your improvements. For major changes, please discuss them in advance to ensure they align with the project's goals.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit the changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.
