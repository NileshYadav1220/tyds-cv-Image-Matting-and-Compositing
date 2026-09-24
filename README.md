Practical 10: Image Matting and Compositing
Aim

To separate the foreground from the background and combine it with another background image.

Technologies Used
Python
OpenCV
NumPy
How it works
Read the foreground image.
Read the new background image.
Resize the background.
Create a mask to identify the foreground.
Extract the foreground.
Extract the background area.
Combine both images.
Display the final composited image.
Run
python matting_compositing.py
Input
person.jpg
background.jpg
Output

The final image contains the selected foreground object placed on the new background.
