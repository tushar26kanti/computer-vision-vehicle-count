# computer-vision-vehicle-count
The vehicle counting system I built is made up of three main components: a detector, tracker and counter. 
The detector identifies vehicles in a given frame of video and returns a list of bounding boxes around the vehicles to the tracker.
The tracker uses the bounding boxes to track the vehicles in subsequent frames. 
The detector is also used to update the trackers periodically to ensure that they are still tracking the vehicles correctly. 
The counter counts vehicles when they leave the frame or makes use of a counting line drawn across a road.
