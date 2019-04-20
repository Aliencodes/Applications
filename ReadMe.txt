ENCODE(c) is a free commercial use text file encrypting software application. It only works on a Windows platform. Below mentioned are some of the components that you will come across while using this application.

1: kFILE1.txt - Contains the "Key" of the text encrypted by you. It is created simultaneously along with eFILE1.txt when you encrypt any text using the application. eFILE1.txt contains the encrypted text and kFILE1.txt contains the "Key" unique to that text. Both files are inter-dependant on eachother and must be stored together at the time of decryption of the text.

2: eFILE1.txt - It is created to store the supplied text in its encrypted form. Whatever text that is received by the application is encrypted and stored in an eFILE1 named text file inside the Encode directory. As mentioned above, a unique "Key" is also generated and stored in kFILE1.txt in the same location. Both these files are required at the time of decryption ofthe message.

3: dFILE1.txt - When you supply both above mentioned files to the application. The application uses them to decrypt the encrypted text. Once decrypted, the plain text is stored in a file named dFILE1.txt inside the Encode directory. You can read the encrypted text in its plain format in this file after the decryption process is complete.

4: iFILE1.txt - Encode(c) also allows you to import a plain text file from the local disk for encryption. Whichever text file from your local disk you need encrypted must be stored as iFILE1.txt inside the Encode directory. The application searches for any file named iFILE1.txt and imports the text inside that file for encryption and subsequently generates an eFILE1.txt containing the encrypted form & a kFILE1.txt containing the "Key" of the text inside iFILE1.txt.

NOTE: Please read all the real time instructions provided by the application at the time of its use in order to prevent any loss of data. It is recommended that a backup of the text being encrypted must be maintained on the user side which may come in handy incase of any unforeseen results at the time of using the application.

For password and more information contact - Mr. Raj Bhakte at raj.bhakte@gmail.com