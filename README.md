# HACKTU5
team: QuirkCoders
Project: driver state detection system
tech used: Yolov5, Pytorch, python

Surveillance system using a camera to alert the driver whenever there is a detection of unawareness, drowsyness or bad habits. (has custom made 7 classes)

Main objective is to prevent accidents at the root cause, i.e. state of the driver and help make the road safer for everyone. Dashcams are becoming a norm in India, and ADAS systems too, with this surveillance system, truck drivers, commercial transport driver, and people who love to tour long distances will always be in a safety mesh just incase they are drowsy or alret them if they are not following decorum of the road. Even new drivers can benefit from this with incorporation of feedback and multipurpose datasets. 

Biggest challenge was (is technically) designing the custom dataset, roboflow has some good options but none which suit the indian facial features and also correspond to a lot of diversity region to region in the country.  For now i tried to make a complete dataset over my own pictures (webcam images), which does recognise my actions and with time and experience i will have to surely expand it suitably for the indian subcontinent. 

other minor challenges are performance issues (for now i have epoch set to 50 because my laptop cannot render very fast)
i would love to have done this on colab but webcam wasnt being supported, so prefferably i will put more time for the training module to better perform with epoch set to 500, (it may take 4 hours) 

please see: it is still very much in progress and as i train the model on further iterations, it may improve for my personal face but may not at all recognise others. 
