# CryptoCom
A CLI that helps in encrypting and decrypting an image with the help of a key , so that the user has the control of the images. You have to install the latest version of NODE and Windows 10 or even higher version OS. JPG/JPEG are lossy formats and hence few pixels are changed in the process. PNG format is a non lossy format and hence images are perfect in this process.
# TechStack
* https://nodejs.org/en/
# Installation
* ___Command___ : npm i -g imcrypt
# Encryption 
* ___Command___ : imcrypt -e (ImageName.format) -i (encryptedImageName.format) -p keyFile.txt
  * __On Success__ :
    *   √ Image read successfully
    *   √ Output image file name is valid
    *   √ Output key file name is valid
    *   √ Image data read successfully
    *   √ Key generated successfully
    *   √ Image encrypted successfully
    *   √ Image saved successfully
    *   √ Key saved successfully
  * __On Failure__ :
    *   ‼  Invalid file path  Please provide a valid file path
# Decryption 
* ___Command___ : imcrypt -d (encryptedImageName.format) -k keyFile.txt -i (decryptedImageName.format)
  * __On Success__ :
     *  √ Image read successfully
     *  √ Key read successfully
     *  √ Decryption successful
     *  √ Image saved successfully
  * __On Failure__ :
     *  ‼  Invalid file path  Please provide a valid file path


# Example :
<li> Image to be encrypted :</li>
<img width="413" alt="image" src="https://user-images.githubusercontent.com/98223018/180658962-4a8f5d02-171e-463c-998a-95c2cc74a57a.png">
<li> Encrypted Image :</li> 
<img width="494" alt="image" src="https://user-images.githubusercontent.com/98223018/180659163-b7cb44dd-d34d-41fd-84e8-5f8d99ff5b75.png">
<li> Key : </li>
<img width="547" alt="image" src="https://user-images.githubusercontent.com/98223018/180659123-f1b0ab7b-e0e1-4914-a28f-1a1fef41f779.png">
<li> Decrypted Image :</li>
<img width="421" alt="image" src="https://user-images.githubusercontent.com/98223018/180659219-be6660c2-20dd-43ec-bbd9-3aa332094eb5.png">


