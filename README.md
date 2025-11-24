# Random Password Generator

A simple Python-based password generator that creates secure random passwords based on user-defined character sets and length.

## Features

- **Customizable Length**: Generate passwords of any desired length
- **Multiple Character Sets**: Choose from:
  - Digits (0-9)
  - Letters (a-z, A-Z)
  - Special characters (!@#$%^&*, etc.)
- **Flexible Combination**: Mix and match different character types
- **Interactive CLI**: User-friendly command-line interface

## Requirements

- Python 3.x
- Standard library modules (no external dependencies):
  - `string`
  - `random`

## Installation

1. Clone this repository or download the notebook file:
```bash
git clone https://github.com/suryansh25bai10281-sketch/cse-project.git
```

2. No additional installation required - uses Python standard library only

## Usage

### Running in Google Colab

1. Open the notebook in Google Colab using the badge at the top of the file
2. Run the code cell
3. Follow the interactive prompts

### Running Locally

If you want to run this as a standalone Python script:

1. Extract the code from the notebook cell
2. Save it as `password_generator.py`
3. Run: `python password_generator.py`

### Interactive Steps

1. **Enter Password Length**: Specify how many characters you want in your password
   ```
   Enter password length: 12
   ```

2. **Select Character Sets**: Choose one or more options:
   - `1` - Add letters (a-z, A-Z)
   - `2` - Add digits (0-9)
   - `3` - Add special characters (!@#$%, etc.)
   - `4` - Exit and generate password

3. **Generated Password**: The program will display your random password

### Example

```
Enter password length: 16
Choose character set for password from these :
         1. Digits
         2. Letters
         3. Special characters
         4. Exit
Pick a number 1
Pick a number 2
Pick a number 3
Pick a number 4
The random password is aB3$xY9@mK2!pQ7#
```

## How It Works

1. User inputs desired password length
2. User selects character sets to include (can select multiple)
3. Program combines selected character sets into one pool
4. Randomly selects characters from the pool until password reaches desired length
5. Displays the generated password

## Security Note

This generator uses Python's `random` module, which is suitable for most password generation needs. For cryptographically secure passwords in production environments, consider using `secrets` module instead of `random`.

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is open source and available for educational purposes.

## Author

[suryansh25bai10281-sketch](https://github.com/suryansh25bai10281-sketch)

## Project Link

[GitHub Repository](https://github.com/suryansh25bai10281-sketch/cse-project)
