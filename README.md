# pillow-tesseract-open-cv-and-matplot-lib
# ocr (optical character recognization) sorry for spelling
ocr  can read or recognise text from a image

ocr can help search index (videos and images)
example (newspaper)
tesseract ocr was developed a long time .who cares btw

##open source software
    publically available for publically for free
    oss that can be freely accesed and shared and modified 
    ocr is oss
    
    based on community
    
gpl(geniu public librabry) licence
bsd licence (https://en.wikipedia.org/wiki/BSD_licenses#3-clause_license_(%22BSD_License_2.0%22,_%22Revised_BSD_License%22,_%22New_BSD_License%22,_or_%22Modified_BSD_License%22)  
maintain minimum amount of legal aid

tesseract project runs by the google(apache licencce )   i dont have driving licennce
py tesseract help us to use tesseract(gpl licence)


##py tesseract library
image_to_string=take an image return the result of ocr
inspect.getsource() = take a function and provide the source code of that.which u dont wanna see
 # in jupyter notebook there is easy way just  type the function with two question mark at end
  pytesseract.image_to_string??
  and here we go
  
  wait wait it not so easy
  you will be needing help (https://tesseract-ocr.github.io/tessdoc/Command-Line-Usage)
  and some more(https://github.com/madmaze/pytesseract/blob/d1596f7f59a517ad814b7d810ccdef7d33763221/src/pytesseract.py#L116)
  these links will take u to the command line help center and if u read that u must have understtod that it is so tricky so leave and go watch u tube
  in that big code there is fucntion called prepare which save our image for pillow
  
lets learn more about tesseract 
well we have some noisy bitches u know what i mean they don't show u clearly

if u use <b> pytesseract.image_to_string() on those bitches u see that ur code fails and u suck
 so modify your code now
  
  when u have noisy bitches it better to be a dog i mean u can try convert the color or colour scale of image . may be to gray or grey 
  these experimentation can help u or fuck u hard
  
  u r an idiot if u dont know how to convert an image lemme tell u
  u just use convert fuction and pass "L"
  your image will be convert
   and then u try ur ML program like ocr and other image processing
  well colour or color manipulation help also in facial recognization .i am not there but one day
  # binirisatiom
  is also another method of image processesing it will convert the pixal into either black or white .if a pixel  is above or below certain type or intensity it will be converted to black or white 
  how u doing
  convert(1) will help
  or u can do it by ur own like 255=white and 0=black
  itererate through every pixels 
  for i in range(imagename.width):
    for j in range(imagename.height):
      if imaagename.getpixel((i,j)>threshhold:
        imagename.putpixel((i,j),0)
  similarly for less value
  
  and now i am a genius
  
   
  
  



