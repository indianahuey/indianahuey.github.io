## Sans: Clean and Filtered Text from PDF Book Scans

![](/example.png)

The purpose of this project is to create a lightweight application, which converts PDFs of text to more readable text files that remove excess information—i.e. serifs and long parenthetical citations—while maintaining helpful information, such as headers and indentation. 

The main tasks of the application will be to read in text from images using optical character recognition (OCR), detect the difference between parenthetical citations and remarks that happen to be in parentheses, and output a nicely formatted document in editable sans serif text with parenthetical citations omitted.

The result should be a solution for turning messy and difficult-to-read PDF scans of books into clean, legible, and excess-free documents.

### Project Goals

1. Obtain/create a dataset for: OCR, parenthetical citation vs. remark, header vs. body
2. Train a neural network to detect the above classes.
3. Implement formatting for output documents.
4. Package it all together into an user-friendly app.

### Challenges

1. How to deal with important non-text information—e.g. images, tables, graphs.

Author: Indiana
