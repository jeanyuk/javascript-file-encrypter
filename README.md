# javascript-file-encrypter
JavaScript File Encryption App:
- Source code - here: https://tutorialzine.com/2013/11/javascript-file-encrypter
- Demo - here: https://demo.tutorialzine.com/2013/11/javascript-file-encrypter/
- Download original - here: https://demo.tutorialzine.com/2013/11/javascript-file-encrypter/javascript-file-encrypter.zip

Changes:
- Updete JQuery.
  Download latest jquery-3.3.1.min.js, save this to assets/js,
	and include this from local file. Now this can working without Internet-connection.
  
- Change background color to grey, for step 3. This color have more contrast with white words and red button.

- Loading passwords by file:
	Add upload-button for load password from text file. Style added.
	Add openFile function there to load text field by file value.
  
- Change source code to do downloading files without base64 encoding.
	There was been double Base64 and file size was been growing.
	Now all files can be downloading as binary data. Base64 using only for pre-cumputing.
  
- Add "Salted__" checking for encrypted file, when decryption.

- folder assets renamed to index_files. Now this folder is autocopyable when index.html copyed.
