# DKNSB intern assignment

The problem statement here is to extract details from the given pdf file. These details include information based on both textual part and symbol images in the pdf document file.

![result_Page_1](https://user-images.githubusercontent.com/104096164/203389931-613f086f-1404-4780-b13a-7225e90d9f1c.jpg)


We want to extract the device name,ref,lots and quantity. Also we want to get a sequence of given symbols.


For this I am using two main techniques :
    
i) Optical Character Recognition using PYTESSERACT : Using this we will extract details like device name,refs,lots and quantity.

ii) Template matching : We are using template matching technique to find the coordinates of symbols based on the symbol templates.
