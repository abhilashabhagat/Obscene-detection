Steps for obscene detection.

Downloaded the data set online .
Developed one function which extracts image features for each image in image paths Returned features is a numpy array with shape (len(img_paths), 2048).
Trained model on NSFW (Non safe for watch)   and SFW( safe for watch) images.
1=presence of NSFW content and 0= absence of NSFW content
Tested on images in test folder.
Tried model on video.
First extracted frame in data11 folder and time information on video.
Tested model on images in data11 folder .
Finally prepared one data frame which include frame,time and presence of NSFW content column. 
Model is saved for future use.
