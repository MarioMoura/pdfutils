# Pdf Utilities
A set of shell scripts to manipulate pdf files. Most of them depend on pdfjam.

## pdfstrip

Removes a list of pages from a pdf.

## pdfsplit
Split a pdf into odd and even pages

## pdfminibook
Transform a pdf by reordering the pages(1,3,4,2,5,7,8,6,...), merging the pages 2 by 2 and flipping them.

## pdfindex
Create indexes(some applications call them bookmarks) in pdfs using GhostScript. The program implements a little markup language as the Gs syntax is cumbersome.

## pdfgetindex
Extracts the indexes(booksmarks) of pdf files and outputs markings intended to be used with pdfindex. This program depends on pdftk.
