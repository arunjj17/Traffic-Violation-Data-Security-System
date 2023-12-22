# Traffic-Violation-Data-Security-System

Since the road resources are limited and the number of vehicles on road are increasing at a tremendous rate, traffic monitoring has become a huge challenge and higher
management costs have resulted in implementing a manual traffic monitoring system.Many traffic violations are difficult to capture with human observation. It is incontrovertible that a more intelligent and less cost scheme to solve the traffic management problem is necessary. In this paper, we aim to design a smart traffic management system using image processing, which can identify a vehicle’s license plate and add the violations in a blockchain. The computerised traffic monitoring system relies heavily
on licence plate detection.

The algorithm uses Canny Edge Detection to detect license plate. Tesseract is used as an OCR engine to recognize the characters from the detected license plate. OpenCV module is used with python for image processing and cloud storage is used to store the details of registered license plates. IoT cameras will be placed at every junction and the license plates of traffic violators will be captured. Then the license plate number along with the violation will be added to blockchain and a notification will be sent
to violator. If the license plate is not registered, then the anomaly will be reported to Motor Vehicle Department.
