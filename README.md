
## Advanced Keylogger
Advanced Keylogger in Python with screenshot, microphone, webcam pictures taking capabilities and then send these files through email.


## Installation
- Download Python and Install it.
- Make sure all the associated modules are installed. I've added all the modules in the requirements.txt file.
- If any of the module is not in the requirements.txt file then open Command Prompt & type
- pip install ModuleName

    
## Working

- Open up a Command Prompt and Change to the directory the program is placed and execute the AdvancedKeylogger.py file.
- Creates a directory to temporarily store information to exfitrate
- Then using multiprocessing 4 features work together simultaniously: (Timeouts and ranges can be adjusted) 
- Open the graphical file manager and go to the C://Users/Public/Logs directory to watch the program in action.
- After all the .txt and .xml files are grouped together and encrypted to protect sensitive data
- Then by individual directory, the files are grouped and sent through email by file type with regex magic
- Finally the Log directory is deleted and the program loops back to the beginning to repeat the same process.
- After files are encrypted and sent to email, download them and place them in the directory specified in Decryptor.py and run the decrypt file in command prompt.



## Features

- Logs pressed keys
- Takes screenshots every 15 seconds
- Records microphone in 10 seconds segments
- Takes webcam picture every 5 seconds
- Gets all the essential network information -> stores to log file (takes about a minute)
- Gets the wireless network ssid's and passwords in XML data file
- Retrieves system hardware and running process/service info
- If the clipboard is activated and contains anything -> stores to log file
- Browsing history is retrieved as a JSON data file then dumped into a log file







## Screenshots


Encrypted data

![encrypt](https://user-images.githubusercontent.com/69382363/201069201-d8096ecb-3109-4c9b-8fd4-04fe3234672c.PNG)

Decrypted data

![decrypt](https://user-images.githubusercontent.com/69382363/201069218-21f2ac37-d354-4fa4-8496-854fe3feebb1.PNG)

Mail 

![mail](https://user-images.githubusercontent.com/69382363/201069224-5aa17950-8efb-44cd-9082-2f10e07d6309.PNG)
## Authors

- [@aniket167779](https://github.com/aniket167779)


## License

[MIT](https://choosealicense.com/licenses/mit/)


![Logo](https://user-images.githubusercontent.com/69382363/201074719-6a6e156b-0095-4efc-be84-2d5ea9cf8787.png)

