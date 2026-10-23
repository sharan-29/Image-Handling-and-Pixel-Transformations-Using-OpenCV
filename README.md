# Image-Handling-and-Pixel-Transformations-Using-OpenCV 

## AIM:
Write a Python program using OpenCV that performs the following tasks:

1) Read and Display an Image.  
2) Adjust the brightness of an image.  
3) Modify the image contrast.  
4) Generate a third image using bitwise operations.

## Software Required:
- Anaconda - Python 3.7
- Jupyter Notebook (for interactive development and execution)

## Algorithm:
### Step 1:
Load an image from your local directory and display it.

### Step 2:
Create a matrix of ones (with data type float64) to adjust brightness.

### Step 3:
Create brighter and darker images by adding and subtracting the matrix from the original image.  
Display the original, brighter, and darker images.

### Step 4:
Modify the image contrast by creating two higher contrast images using scaling factors of 1.1 and 1.2 (without overflow fix).  
Display the original, lower contrast, and higher contrast images.

### Step 5:
Split the image (boy.jpg) into B, G, R components and display the channels

## Program Developed By:
- **Name:** BLESSING S
- **Register Number:** 212224230039

  ### Ex. No. 01



1. **Original RGB Image**

```python
plt.imshow(img_rgb, cmap='viridis')
plt.title("Original RGB Image")
plt.axis('off')
plt.show()
```

2. **Image with Line**

```python
plt.imshow(line_img, cmap='viridis')
plt.title("Image with Line")
plt.axis('off')
plt.show()
```

3. **Image with Circle**

```python
plt.imshow(circle_img, cmap='viridis')
plt.title("Image with Circle")
plt.axis('off')
plt.show()
```

4. **Image with Rectangle**

```python
plt.imshow(rectangle_img, cmap='viridis')
plt.title("Image with Rectangle")
plt.axis('off')
plt.show()
```

5. **Image with Text**

```python
plt.imshow(text_img, cmap='viridis')
plt.title("Image with Text")
plt.axis('off')
plt.show()
```

6. **Original RGB Image**

```python
plt.imshow(image_rgb)
plt.title("Original RGB Image")
plt.axis("off")
plt.show()
```

7. **HSV Image**

```python
plt.imshow(image_hsv)
plt.title("HSV Image")
plt.axis("off")
plt.show()
```

8. **Grayscale Image**

```python
plt.imshow(image_gray, cmap="gray")
plt.title("Grayscale Image")
plt.axis("off")
plt.show()
```

9. **YCrCb Image**

```python
plt.imshow(image_ycrcb)
plt.title("YCrCb Image")
plt.axis("off")
plt.show()
```

10. **HSV to RGB Image**

```python
plt.imshow(image_hsv_to_rgb)
plt.title("HSV to RGB Image")
plt.axis("off")
plt.show()
```

11. **Image with Inserted Image**

```python
plt.imshow(image_rgb)
plt.title("Image with Inserted Image")
plt.axis("off")
plt.show()
```

12. **Resized Image**

```python
plt.imshow(resized_image_rgb)
plt.title("Resized Image")
plt.axis("off")
plt.show()
```

13. **Cropped Region (ROI)**

```python
plt.imshow(roi_rgb)
plt.title("Cropped Region (ROI)")
plt.axis("off")
plt.show()
```

14. **Flipped Horizontally**

```python
plt.imshow(flipped_horizontally_rgb)
plt.title("Flipped Horizontally")
plt.axis("off")
plt.show()
```

15. **Flipped Vertically**

```python
plt.imshow(flipped_vertically_rgb)
plt.title("Flipped Vertically")
plt.axis("off")
plt.show()
```


## Output:
<img width="534" height="420" alt="image" src="https://github.com/user-attachments/assets/ac545ea5-0ef8-4703-b6a5-9d7403b5629b" />
<img width="521" height="409" alt="image" src="https://github.com/user-attachments/assets/4bee697b-4fdf-4f14-989a-9b3f652e9c9d" />
<img width="514" height="412" alt="image" src="https://github.com/user-attachments/assets/98864e07-cf61-48ca-9db2-74025b89ecb1" />
<img width="535" height="411" alt="image" src="https://github.com/user-attachments/assets/6534574c-8317-4f75-b142-09434055154e" />
<img width="524" height="414" alt="image" src="https://github.com/user-attachments/assets/7b63694d-2752-4487-b398-a791155d5b9b" />
<img width="544" height="406" alt="image" src="https://github.com/user-attachments/assets/543960dc-67c1-4e33-a6ff-fc40c6f6b463" />
<img width="530" height="407" alt="image" src="https://github.com/user-attachments/assets/49678848-bd00-40d8-92e2-36e45defe19b" />
<img width="523" height="408" alt="image" src="https://github.com/user-attachments/assets/92623298-97a7-417a-b3d5-8c60db062582" />
<img width="542" height="405" alt="image" src="https://github.com/user-attachments/assets/1d9338a9-dc94-4510-9b29-058db5707813" />
<img width="532" height="402" alt="image" src="https://github.com/user-attachments/assets/1b9b3df8-3ee9-4018-a568-a43e7a792ff9" />
<img width="521" height="400" alt="image" src="https://github.com/user-attachments/assets/26669bb6-0b65-4594-b73f-e21f477611d3" />
<img width="488" height="405" alt="image" src="https://github.com/user-attachments/assets/077996af-81a5-4daf-9054-42d04c5c1656" />
<img width="405" height="402" alt="image" src="https://github.com/user-attachments/assets/cb365748-f166-4034-9fc9-e2490ab9ca56" />
<img width="535" height="408" alt="image" src="https://github.com/user-attachments/assets/dcdad392-f887-4155-86ca-170a334620fc" />
<img width="530" height="417" alt="image" src="https://github.com/user-attachments/assets/68cd1d81-4d96-45a8-a93e-2ec50a4e456a" />













## Result:
Thus, the images were read, displayed, brightness and contrast adjustments were made, and bitwise operations were performed successfully using the Python program.

