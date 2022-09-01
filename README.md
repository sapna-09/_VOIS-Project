# _VOIS-Project
**Tesseract- Check MICR Extraction.ipynb -** is used to extract the IFSC code, Cheque No and Account No. using MICR.

![image](https://user-images.githubusercontent.com/76240391/187831279-5f620c24-4286-4c08-9dff-fabe4dcef20e.png)

![image](https://user-images.githubusercontent.com/76240391/187831316-d3b8a6a3-0347-4db6-994a-742ad1b249b7.png)

![image](https://user-images.githubusercontent.com/76240391/187831352-068bef4d-e1f4-43db-b952-c579bfbb3b5a.png)

**SgnatureVerification.ipynb -** is used to verify the signature of the user and match it with the database to declare if the signature is forged or real. Given file is trained 
with 12 people signature. They signature is present in form of AAABBB_CCC. This is for our reference.<br />
AAA - Denotes the person who has signed the document.<br />
BBB - Denotes the person to whom the signature actually belong to.<br />
CCC - Denotes the number of attempts<br />
For Genuine signature => AAA==BBB.<br />

![image](https://user-images.githubusercontent.com/76240391/187831726-db2541e7-2438-4a41-9ee5-f336fd2ec0fa.png)

https://drive.google.com/drive/folders/11d9Zpn1OkIPjsIIvEUQqpa_CVg20Xfyj?usp=sharing
