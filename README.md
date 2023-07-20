# Auxo_ai - assigment:

The entire assignment is developed using python.

Problem 1:

• Given a set of PDF documents, create Python functions to break down each file into sections
based on the table of contents.

• Store the sections of each PDF in an appropriate data structure, including the content and
metadata such as the PDF file name and page number.

Solution:
1. The code breaks the PDF documents on each book mark corresponding to each section.
2. The data is stored in two hash map.
3. The first hash map contains the page number and the section name of each entry in the table of contents.
4. The second hash map contains the page number and the content of the particular page number.
5. Hash map was preferred as it would reduce the time complexity and make it easier to extract data of the particular page number(in constant time).
6. The pdf names are stored in a list.
7. Further the stored data is then written into individual section data in a docx file and is saved into the system.

   Libraries used:
   1. PyPDF2
   2. python-docx
   

