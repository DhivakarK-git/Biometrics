# Biometrics
The ongoing pandemic has forced the education sector to plan continuity in learning and exams. Therefore, it is necessary to proctor and monitor the students.
The project aims to use iris movement to ensure protection from malpractices.

## Authentication
Capturing the duration between 2 keypresses, the duration of pressing down a key, and the duration between the current key release and the next key press can provide insights about the user.
The next time the user logs in, by comparing his/her current typing pattern with his/her previous typing patterns, the platform can authenticate whether the logged in user is legitimate or fraudulent.
It is a classification based problem, where different typing patterns have been matched and clustered under the same umbrella.

## Monitoring/Proctor
The monitoring system detects if the student moves the face away from the screen or sees anywhere other than the screen. The traditional means for doing so,  still happens to be gaze estimation by approximating the direction in which the face is looking at. This, however may not seem to be effective since it misses the quick glances one makes without actually turning the head.

So this project explores the possibility of tracking where a person is looking at by the x and y axis displacement of the iris from the center of each eye. Based on this displacement values, any company with a certain set of business rules can implement an alogrithm that best suits their needs and succesfully proctor an exam.

## Traits Used 
		a)	Keystroke dynamics
		b)	Eye movement
