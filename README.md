# Cryptography_Task

## Convert a simple plaintext into an MD5hash using online resources and embed the hash value into an image.

### Perform the following operations:

*  Open the text file and write the content you want to send to the user.
*  Copy the text. Convert the text into an MD5 hash by using online cryptography websites.
* After converting it from plaintext to a hash, paste it in the document, and save it.
* Open the command prompt and embed the data into an image using the command:
```
Copy /b <imagepath>+<path of text file><space>output.jpg
```
* You will find the file in the destination folder. Send it to the client through an email.
* Once the client receives the email, tell them to retrieve the hash by opening the image
file with Notepad. Search for the MD5 hash (it will be at the end of the file).


## After completing the previous task, where we must use the Snow tool to hide the data in text files using the White-Space technique.

### Perform the following operations:

* Download the SNOW tool and extract the file
* Go to Snow Directory and enter the below command to hide the secret message with
another document using the password.
* Enter the below commands
 ```
snow –C –m “Any secret message to be hidden” –p “vishwa123” sample.txt
sampleoutput.txt
```
* You can see a new file in the directory, and you can open and see the extra white spaces
shown in the document.
* Determine the hidden messages from sample output using the below command:
 ```
snow –C -p “suyash123” sampleout.txt
```

