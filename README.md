This project is a face recognition-based attendance system that integrates with Firebase for real-time database and storage management. It captures video using a webcam, processes the video frames to detect and recognize faces, and then matches the detected faces against a preloaded list of known encodings. When a match is found, the system retrieves the corresponding student's information from the Firebase database and updates the attendance record if sufficient time has passed since the last attendance.