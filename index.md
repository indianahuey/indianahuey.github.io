## Minimalistic Writing from PDF Literature Scans

The purpose of this project is to create a lightweight application, which converts PDF's containing text to more readable text files that remove excess information—i.e. sans serif, sans long parenthetical citations—and maintain helpful information, such as headers and indentation. 

The main tasks of the application will be to read in images of text using optical character recognition (OCR), detect the difference between parenthetical citations and remarks that happen to be in parentheses, and output a nicely formatted document in editable sans serif text with parenthetical citations omitted.

The result should be a clean solution to turning messy and difficult-to-read PDF scans of literature into more legible and excess-free writing.

### Project Goals

1. Obtain/create a dataset for:
    \n\t(a) OCR
    \n\t(b) parenthetical citation vs. remark
    \n\t(c) header vs. body
2. Train a neural network detect the above differences.
3. Implement formatting for output document.

### Challenges

1. How to deal with important non-text information—e.g. images, tables, graphs?
