# Cipher
#### By Ash Laidlaw

## Project Goals

The goals of this project are to create a custom module for Drupal. The module is a form input, which takes in three different user inputs: a number, a direction (left or right), and a phrase. The output will take the user's input, and code the phrase based on the other parameters. For example, if a user enters 3, right, and hello, it will output "khoor". That is "hello" shifted three letters to the right.

## Build Instructions

To duplicate this project, please follow the steps below:

  1. Navigate to https://github.com/Yhbv24/cipher to see the project.
  2. Clone the rep to your computer.
  3. Extract the database from the `db-backup` folder in the `sites` folder.
  4. Start the MAMP servers (if you don't have MAMP, please see https://www.mamp.info/en/ for more information) and then navigate to localhost:8888/phpmyadmin in your web browser.
  5. Import the database you extracted.
  6. Stop the MAMP servers, and change the webserver directory to the project folder.
  7. Start the MAMP servers again, and navigate to localhost:8888.

## Specs

| Input | Output |
|-------|--------|
| 3, right, hello | khoor |
| 2, left, great | epcyr |
| 3, right, hello. | khoor. |
| 6, left, hey! how are you? | bys! biq uly sio? |
| 4, left, HI THERe | de pdana |

## Technologies Used

* Drupal 7
* PHP

## Licensing

MIT License, © Ash Laidlaw 2017
