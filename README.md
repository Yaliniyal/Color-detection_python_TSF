# Color-detection_python_TSF

DIRECTIONS AND FUNCTIONS USED:

#Creating argument parser using argparse to take image path from command line
#Here I,ve used command prompt
#Reading the image with opencv command imread
#declaring global variables for clicking and position of axes x and y
#Reading csv file with pandas by read_csv and giving names to each column
#function to calculate minimum distance from all colors and get the most matching color
#function to get x,y coordinates of mouse double click
# calling the image by namedWindow and indicating by mouse
#filling rectangle by the command cv2.rectangle(image, startpoint, endpoint, color, thickness)-1 fills entire rectangle 
#Creating text string to display( Color name and RGB values )
#showing text , the name of color by using cv2.putText(img,text,start,font(0-7),fontScale,color,thickness,lineType )
 #For very light colours we will display text in black colour
 #Break the loop when user hits 'esc' key 
