# READ AND WRITE AN IMAGE
## AIM
To write a python program using OpenCV to do the following image manipulations.
i) Read, display, and write an image.
ii) Access the rows and columns in an image.
iii) Cut and paste a small portion of the image.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Choose an image and save it as a filename.jpg
### Step2:
Use imread(filename, flags) to read the file.
### Step3:
Use imshow(window_name, image) to display the image.
### Step4:
Use imwrite(filename, image) to write the image.
### Step5:
End the program and close the output image windows.

```

## Program:

# Developed By: FAWZIYA A
# Register Number : 212220230017
# To Read,display the image
import cv2
image=cv2.imread("1.jpeg")
cv2.imshow("image",image)
# To write the image
cv2.imwrite("image2",image)
# Find the shape of the Image
print(image.shape)
# To access rows and columns
for i in range(70,90):
for j in range(110,170):
image[i][j]=[0,0,0]
# To cut and paste portion of image
image[2000:2700,2000:2700]=image[1000:1700,1000:1700]

```

## Output:

### i) Read and display the image

![image](https://user-images.githubusercontent.com/75235022/161051026-3fa6f6ba-6f99-4eea-8ae5-1ff3a93eed7c.png)

<br>
<br>

### ii)Write the image

![image](https://user-images.githubusercontent.com/75235022/161051129-3ca061d9-6e70-41c2-ac23-b17229b5ee3b.png)

<br>
<br>

### iii)Shape of the Image

![image](https://user-images.githubusercontent.com/75235022/161051150-8480b613-33db-4b92-a61b-ae965204ccd6.png)

<br>
<br>

### iv)Access rows and columns

![image](https://user-images.githubusercontent.com/75235022/161051253-c4603370-e150-4b54-a5ce-270a0584dc21.png)

<br>
<br>

### v)Cut and paste portion of image

![image](https://user-images.githubusercontent.com/75235022/161051276-eb79d8f9-9396-4440-8fc7-b47640ea3468.png)

<br>
<br>

## Result:
Thus the images are read, displayed, and written successfully using the python program.


