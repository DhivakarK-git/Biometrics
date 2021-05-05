# Iris Tracking

Due to ongoing pandemic and the surge in popularity for online classes and exams, it becomes increasingly important for a system that can ensure no malpractice occurs during such online exams.
Howsoever, the traditional means for checking if the person is lookinf offscreen,  still happens to be gaze estimation by approximating the direction in which the face is looking at. This, however may not seem to be effective since it misses the quick glances one makes without actually turning the head.
So this project explores the possibility of tracking where a person is looking at by the x and y axis displacement of the iris from the center of each eye. Based on this displacement values, any company with a certain set of business rules can implement an alogrithm that best suits their needs and succesfully proctor an exam.

Advantages of a Iris Tracking System over the alternatives:
    • More Accuracy compared to the alternatives. Since direction and movement are easier to detect with iris. Since, iris can be identified much easier in a 2d plane. 
      This also allows us to easily make a threshold for its x axis and y axis movement and figure out the number of times the subject is looking offscreen.
    • More freedom to set rules and regulations. With iris, we can even calculate the time the subject is looking offscreen.    
    • Also, Possibility of identifying if the person is having an aide within the screen as well, with window snapping.
    • Also, can flags users who take a quick glance offscreen, which is often not noticed when the system primarily tracks faces.
    

Disadvantages of a Iris Tracking System over the alternatives:
    • Less precision, due to the fact that most of the time iris is a very small part of the webcam feed. Unlike that of face, the fraction of iris within a frame is significantly less for iris.
    • Quiet taxing on the device it runs on. We figured out even the most efficient algorithms and classifiers required most of the resources of the device. So we assume when running on the web, the device side performance should be good.
    • It requires a very stable and fast internet connection. Since iris is very erratic and calculates the results within a frame rather than interframe, it means that it requires a good o=ping or latency for the best results.
    • As of now Iris Tracking systems don't have an efficient algorithm for gaze estimation. If gaze estimation is included in iris tracking, the system accuracy may improve.
    • Requires a higher fault tolerance than its alternatives.

Future Scope:
	The best iteration of this device is one that is a multimodal with various other features such as face being tracked. Also it necessitates a way for inter frame algorithms and an effective gaze estimation algorithm. The current estimation technique is a bounding box technique, which is indicative of movement only, and flags the user once the gaze crosses this bounding box.

Please additionally download shape_predictor_68_face_landmarks.dat.bz2 from http://dlib.net/files/ and import it into the ipython notebook
