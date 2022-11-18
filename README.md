# smart-visitor
 
- This project focuses on creating a smart visitor recognition system that provides notifications to the owner through the Internet whenever a person comes at the door
- When a person comes at the door, camera sensor captures his/her image and sends it to the ML face recognition module
-  It recognises the face of the user with any of the allowed members and matches the entry timing


Required Packages:
- cv2
- skimage
- face_recognition
- telegram-bot
- PIL
- seaborn, keras (These packages are only required for analysis. Main code can run without it)


How to run the code:
- Telegram bot
   - Make a Telegram bot on the Telegram App referring this link: https://docs.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0
   - Update the bot credentials in constants.py file.
- Smart Visitor Recognition code:
   - Make sure you are in the source directory
   - Make sure you have updated the telegram bot credentials in constants.py file.
   - Run prediction.py file to predict the person who comes to the door.
   - Run data_prep.py to register a new person to the system.
- Analysis Code:
   - Run knn_analysis.ipynb notebook to run the code for KNN classifier.
   - Run svm_analysis.ipynb notebook to run the analysis for the SVM classifier.
   - Run encoding_analysis.ipynb notebook the get analysis on encoding method comparison.
   - Train_test.py code is to be run to make a separate testing folder. This code only needs to run one time and has already been executed so no need to run again.


For any queries, please contact Manjyot singh Nanra(manjyots21@iitk.ac.in) or Sharanya Saha(sharanya21@iitk.ac.in)