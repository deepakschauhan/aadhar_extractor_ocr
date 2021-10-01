# aadhar_extractor_ocr
 
 
 #this use step for windows
 
 
1st step is 

select your dir

C:\Users\Deepak> git clone https://github.com/deepakschauhan/aadhar_extractor_ocr

C:\Users\Deepak> cd aadhar_extractor_ocr

install all lib file so then use this cmd-->> 

C:\Users\Deepak>pip install -r requirements.txt

2nd step is 

C:\Users\Deepak> python aadhaar_read.py

output is

PS C:\Users\Deepak\Desktop> python aadhaar_read.py
Aadhar number is find

---------- AADHAAR Details ----------

AADHAAR Number:  4382 5165 5729


Press Enter To EXIT


 #this use step for Mac
 
 1st step is 

select your dir

C:\Users\Deepak> git clone https://github.com/deepakschauhan/aadhar_extractor_ocr

C:\Users\Deepak> cd aadhar_extractor_ocr

install all lib file so then use this cmd-->> 

C:\Users\Deepak>pip install -r requirements.txt

install brew



gurudev@amontpellier-653-1-353-70 aadhar_extractor_ocr % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

#install brew in tesseract

gurudev@amontpellier-653-1-353-70 aadhar_extractor_ocr % brew install tesseract

#list tesseract

gurudev@amontpellier-653-1-353-70 aadhar_extractor_ocr % brew list tesseract

this is list-->

/usr/local/Cellar/tesseract/4.1.1/bin/tesseract
/usr/local/Cellar/tesseract/4.1.1/include/tesseract/ (19 files)
/usr/local/Cellar/tesseract/4.1.1/lib/libtesseract.4.dylib
/usr/local/Cellar/tesseract/4.1.1/lib/pkgconfig/tesseract.pc
/usr/local/Cellar/tesseract/4.1.1/lib/ (2 other files)
/usr/local/Cellar/tesseract/4.1.1/share/tessdata/ (35 files)


/usr/local/Cellar/tesseract/4.1.1/bin/tesseract this line use for code



ouput 

gurudev@amontpellier-653-1-353-70 aadhar_extractor_ocr % python aadhaar_read.py 

Aadhar number is find

---------- AADHAAR Details ----------

AADHAAR Number:  4382 5165 5729 


Press Enter To EXIT

