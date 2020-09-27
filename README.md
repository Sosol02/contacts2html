
# Contacts2html

Converts a csv file to an html table to allow you to read exported contacts (from google contacts for example) more easily.

## Setup

This program requires a distribution of [guile](https://www.gnu.org/software/guile/) to be installed.

## Usage

Just run `./contacts2html < contacts.csv > contacts.html`, then open the resulting web page in your favorite browser: `firefox contacts.html`.
If you get a permission error, you may need to run `chmod u+x contacts2html` to allow the execution of the program.

## Caveats

This is just a funny script I wrote an evening. Don't expect too much from it :)


