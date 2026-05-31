# Pass Your Word

A simple password generator.

## What it does

- Generates secure random passwords using 'crypto.getRandomValues()'
- Lets you choose password length
- Option to include numbers and symbols
- One-click copy to clipboard
- Works entirely in the browser (no internet required)

## Why I made

Most password generators feel either overcomplicated or too polished. This is a minimal tool that just does one thing: generates strong passwords quickly.

## How to use

1. Open "index.html" in any modern browser
2. Set your desired password length
3. Choose whether to include numbers and symbols
4. Click "Generate"
5. Click "Copy" to copy your password

## Security note

This project uses the browser’s built-in cryptographically secure random generator ('crypto.getRandomValues()'), which is suitable for generating strong passwords.

## Limits

- Maximum password length is capped at 256 characters to prevent browser slowdown. Why the heck do you need a 2183745 character password?

## License

Feel free to use, modify, and share.