# CS408 - Lab 11.2

Westley Foster
November 5, 2025

## Overview

This program implements JavaScript into an HTML file that connects to two AWS 
(Amazon Web Services) endpoints. It simulates a user's inventory by using PUT,
GET, and DELETE requests to allow the user to dynamically fill a table with 
information of an item, including an ID, Name, and Price for said item, and 
the delete feature for any item.

## How to Run

To run the project in VSCode, simply install the Live Preview and Live Server extensions and then go to the
command bar at the top of the IDE. Click on the bar and type in "Live Preview: Start Server". A side window
should appear with your program running in a simulated browser. To better view the project while running 
the server, copy and paste the url in the side window into your own web browser.

Test the PUT, GET, and DELETE requests with the respective buttons. Refresh the page to see changes to the
inventory's table when adding an item or deleting an item.

## Sources and Credits

- Index.html
    - Formatting tables and input with ChatGPT
    - Scripts written with help from ChatGPT
- style.css
    - Majority of CSS written by ChatGPT (buttons, tables, and input container). 
    -td:last-child written with help from Google's AI Overview