# Getting started

* Ensure node.js is installed, then run `npm install` in the root folder.
* To generate random password type `passgen`
* By default, the password length is eight, but to generate a password of desired length, you have to pass `--length` or `-l` option with desired length, e.g., `passgen --length 20`
* By default, the password has alphabets, numbers and symbols, but you can choose not to include number and symbols, e.g., `passgen --no-numbers` or `passgen -nn` for not including numbers
* Similarly for not including symbols you have to pass `--no-symbols` or `-ns` option.
* To save the password in a file, pass `--save` or `-s` option. Currently we saving the password in `passwords.txt` file in the root folder