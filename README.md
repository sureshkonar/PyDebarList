# Debarred-List-Automater for College Assessments 🤖
In Simple word this is a Excel sheet Automator Program using Openpyxl Python Library for large Datasets where the task is to select the values among the dataset between the specified range and then traversing the selected data into the new sheet of the same excel file 

![HappyFaceExcelGIF](https://user-images.githubusercontent.com/74930080/188192262-b8040bd4-65eb-41ee-a3d0-bdc98b868709.gif)

# Problem Statement ➡️
To implement a python program which automates the process of finding/selecting the data lying in the specified range and traversing them into a new sheet of the same Excel (.xlsx file) 

# Note ⚠️
         1) This Program will only work for the specified format file (format.xlsx).
         2) File generated By this program in .xlsx format cannot be opened using MS Excel As the generated file violates the File integrity policy of MS Excel.
         3) So to overcome this you can use google spreadsheet website i.e (Google Sheets) 
         4) Now open generated .xlsx file in google sheets website to view the changes made by the python code

# Problem Description ➡️ 

This is a Python Code which will 🎯

a) traverse an ExcelFile (format.xlsx)

b) sort the data according to the range such that eg: (80<x<90)

c) now this sorted data is been appended on new sheet of the same (format.xlsx) file according to the mentioned range 

d) the index of entries is also been maintained in a separate sheet called "Index". Where we have total number of entries & students

  
# Format Excel File ( format.xlsx )

[format.xlsx](https://github.com/sureshkonar/Debarred-List-Automator/files/9479612/format.xlsx)

The Excel file that is supposed tp be used in this program  should follow the Columnns Format exactly mentioned in the format xlsx file in the files section

![image](https://user-images.githubusercontent.com/74930080/188196700-c7b2c29b-d6d1-421c-a3cb-15a17fc6cdd6.png)![image](https://user-images.githubusercontent.com/74930080/188196865-01493378-9c99-4dce-babb-ddd8abd4d9a9.png)

# Technology Stack 📝

1) python 3.9 

![image](https://user-images.githubusercontent.com/74930080/188194573-760957a1-d16f-4864-a83c-89d7182206f1.png)

2) pandas Library 

![image](https://user-images.githubusercontent.com/74930080/188195478-9730bc9e-18b1-4122-b826-ea61e7a570a0.png)

3) tracemalloc library

![image](https://user-images.githubusercontent.com/74930080/188195543-f7410d53-2526-4e91-8104-508a181adc19.png)




