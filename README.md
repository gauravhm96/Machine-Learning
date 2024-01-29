# Reliability test and improvement of a sensor system for object detection

An existing measurement system for detecting the position of the first echo (i.e. first reflection) of a pulsed ultrasonic beam shall be assessed and improved.

a) Introduction: Getting familiar with the measurement equipment and the measuring methods. Write a short literature review on ultrasonic distance measurement and describe the
ML method used for finding the first reflection. The measurement equipment and experimental setup will be provided in room 8-102a or the Robolab.

b) Distance measurement data collection (data set #1) using different objects and persons. There are three distances available. First, the FIUS inbuilt distance measurement (dFIUS).Second, the distance that you calculate from the first echo position. The first echo position is detected by the machine learning-driven first echo detection algorithm (dML). Third, the manually measured distance using a folding meter stick (dMAN).Compare the distances dFIUS, dML, and dMAN. Data set #1 must consist of at least 1000 measurements. Store ADC data and all distances. Record the experimental setup properly, including all environmental conditions and photos of the objects, persons,and the measurement situation. Submit data set #1.

c) Write software (Python or C++) that automatically calculates and displays the distance dML between the sensor and the first reflection using the ML first echo detection algorithm given.

d) Conduct the same experiment as done in part b), this time with your self-written software for distance calculation (data set #2).Measure the distances manually. Compare the results and create a confusion matrix. If the deviation between the manually measured distance (dMAN) and the automatically created distance (dML. dFIUS) is less than 1 cm, then it shall be counted as a hit. Otherwise, it’s a fail. Submit data set #2 and the confusion matrix.

e) Improve the precision of the first echo detection by searching the maximum peak within the time window indicated by the  ML-driven automatic search. Then conduct experiment b) again (data set #3). Create a confusion matrix

f) Research on and implementation of improvements such as:
- Improve decision speed. Submit the measuring data and the result.
- Improve measurement accuracy. Submit the measuring and the result.
- Systematically search for and report the limits of the system.
- Develop and implement software for cropping the first echo’s data. After finding the position of the first echo, the part of the time signal near the echo shall be stored in a file. There should be an opportunity to pre-set the length and the position of the time window that shall be stored.
- Develop a GUI for displaying the signal and the results. It shall be used for settings (e.g. length of the time window, position of the time window relative to the first echo position) too.
Alternatively, extend the existing GUI. - Analyze systematically results, data, and FFTs, especially of false predictions, and give reasons, e.g. based on research
scientific papers and books on ultrasonic physics.


g) Write a report and submit it. The report should contain theory, HW, SW (if applicable), data processing, measurement settings, variations, results, and photos. It also should explain briefly the context of the project to the module.

h) Give a demonstration of your system. The demonstration date will be announced
