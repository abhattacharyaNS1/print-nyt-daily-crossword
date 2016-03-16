# print-nyt-daily-crossword
A script that print's today's NYT crossword puzzle.

## How to use

* Make sure you're subscribed to the [NYT Crossword](http://www.nytimes.com/crosswords/index.html). You can't access the crosswords without a subscription.
* Edit `print-crossword` and define the `username` and `password` variables with your subscription's credentials. 
* Run the script with no arguments. It will login, download the PDF, and print it to your default printer via `lpr`.
* Optionally, you can make a cron job to automatically print the puzzle, e.g. `0 7 * * * /path/to/print-crossword`.
