To run Face Detection application, have OpenCV setup on Ubuntu 18.04 version. Then, download zip file, open terminal within the folder and run the line 'python detect_faces_video.py --prototxt deploy.prototxt.txt  --model res10_300x300_ssd_iter_140000.caffemodel'
Frame will open up, accessing your webcam and running the detection algorithm. Notice that the application will form a rectangular red box around a human face. It will not detect anything other than a face.
This application comes with built-in libraries that OpenCV offers.
