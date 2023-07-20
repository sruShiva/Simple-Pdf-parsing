# Auxo_ai - Sruthi Shivaramakrishnan

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

How to run the file?
1. Download the new_file.py and save it in your system.
2. Update the paths and run the file to see the output.

Problem 2:

• Develop a simple application, either locally hosted or using open-source frameworks, that
allows users to upload multiple PDF documents.

• After uploading the PDF documents, provide an option for users to submit the documents.

• Upon submission, each PDF document should be divided into sections as described in
Problem 1.

• Users should be able to download the resulting output in a format of your choice.

Solution:
1. Created an api using python flask to upload mutliple documents.
2. Converts the document to docx format and csv formats.
3.  Gives the output as a zip file with the both outputs.


Model working:

1. Upload files using the upload button.

   ![image](https://github.com/sruShiva/Auxo_ai/assets/91767610/fd85236b-5c9f-462d-89e1-6d730db89a57)

2. CLick on submit button to upload button and wait for the files to convert.
3. Once converted, the zip file with the converted files gets downloaded on your local system.
   ![image](https://github.com/sruShiva/Auxo_ai/assets/91767610/1b303209-83e3-4eec-be7f-72c949f81936)
4. The converted files are displayed in the folder.
   ![image](https://github.com/sruShiva/Auxo_ai/assets/91767610/f0fc1aec-f8ca-4c0e-938e-9eb8176fb80a)
5. Docx format helps to view the detailed contents of the file whereas csv helps to view the contents at a glance.

How to run the file?
1. Save the python_auxo_ai folder in your system.
2. Once downloaded, run the main.py file to see the hosted server on local host.









   

