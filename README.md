# Attendance-marker-using-Face-Recognition

1. A realtime face attendance system wherein webcam captured frames will be matched against the existing database images and if the match is found then it’ll store it in a CSV file called ‘Attendance Register’ along with name and time of capture. Only once the file will store the matched image’s details, if the same image is received again then it’ll not update.
Path setting to the directory containing the image database. Read each image and the images array. Append the filenames into a list called Names and remove the extension.

2. Find the face encodings of images in the database and keeping them in a list to use later with incoming frames. 
3. The same process is followed by the first detection face location then getting the face encoding values.
4. Now the incoming images are tested against the previously-stored encodings. Then the face distance is also computed. Lastly, we call the Attendance function along with the person name who is identified.
5. Reading from attendance file, Storing data(Name and Time of entry) if previously not stored.

