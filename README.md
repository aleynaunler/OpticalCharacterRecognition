# OpticalCharacterRecognition
OCR system
This project aims to transfer the information on the identity card to the computer environment with OCR. First, identity card divided the region with Template matching as relevant region with efficient region like as name,surname,ID,birh date,document no, valid until.Then that ROI's convert to the gray scale form and then using tesseract every ROI's at the same time every information read from image and transfered to digital.



That working logic is same the scanner.


Template matching is a technique for finding areas of an image that are similar to a template.Wholeimage of ID’s is a source image and informations on the ID are template.Template matching is a method for searching and finding the location of a template image in a larger image.OpenCV comes with a function cv.matchTemplate() for this purpose.I defined to source image as front of turkish identity and template as part of information on the identity such as surname,identity no,date of birth.I cropped to every part of information and give the system as template.Several comparison methods are implemented in OpenCV,I used cv2.TM_CCOEFF is a coefficient matching method.The method is simply used to make the template and image zero also make the dark parts of the image negative values and bright parts of the image positive values



OCR stands for Optical Character Recognition. It is used to read text from images such as a scanned document or a picture. This technology is used to convert, virtually any kind of images containing written text typed, handwritten or printed into machine-readable text data.




The ID used is completely an example and taken from the internet.




Documents such as passports or any other document in different sizes and characters can be processed in the same way.
