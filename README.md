# leave-liability-pdf-splitter
Splits PDFs from leave liability into individual files

## Dependent Python 3 Libraries
* PyPDF2
* re
* glob
* logging

## How to use
Put all the PDF files received from the HR department inside the `./input` folder.

Run `python script.py` and wait for it to finish.

You can update the `begin_keyword` and `end_keyword` to modify the behaviour.

Files generated can be found in the `./output` folder (ensure its been created!).
