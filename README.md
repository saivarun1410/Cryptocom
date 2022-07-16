# Cryptocom
A CLI that helps in encrypting and decrypting an image with the help of a key , so that the user has the control of the images. You have to install the latest version of NODE and Windows 10 or higher version OS. JPG/JPEG are lossy formats and hence few pixels are changed in the process. PNG format images are perfect in this process.
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
# Command Options
*  help$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ # prints other options
* -e, --encrypt$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ # The image to encrypt
* -d, --decrypt$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ # The image to decrypt
* -c, --clear$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ # Clear the console Default: false
* --noClear$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ # Don't clear the console Default: true
* -v, --version$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ # Print CLI version Default: false
* -k, --key$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$ # The key to use for decryption Default: false
* -i, --outputImageFileName$~~~~~~~~~~~~~~~~~~~~~~$ # The output image
* -p, --outputKeyFileName$~~~~~~~~~~~~~~~~~~~~~~~~~$ # The output key
