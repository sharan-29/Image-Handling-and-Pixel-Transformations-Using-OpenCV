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
- **Name:** Sharan Kumar G
- **Register Number:** 212224230260



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
<img width="387" height="506" alt="image" src="https://github.com/user-attachments/assets/17ac93cd-ab5f-47cc-8fb2-734516b43152" />
<br>
<img width="395" height="515" alt="image" src="https://github.com/user-attachments/assets/afc771b3-d587-4ebd-945e-6f6186b0d67e" />
<br>
<img width="382" height="512" alt="image" src="https://github.com/user-attachments/assets/a39cb04b-3c1c-442f-9718-b01bd91265db" />
<br>
<img width="392" height="515" alt="image" src="https://github.com/user-attachments/assets/de7490ce-20e8-4855-9279-690164fabcbc" />
<br>
<img width="393" height="522" alt="image" src="https://github.com/user-attachments/assets/9d18054f-04de-417e-80ce-f9ade4bf6135" />
<br>
<img width="380" height="510" alt="image" src="https://github.com/user-attachments/assets/da31b8ed-d5a6-4a26-bb1e-06dfd28641f8" />
<br>

<img width="397" height="508" alt="image" src="https://github.com/user-attachments/assets/b82a97f0-5613-42d7-9553-efa2ee9832e1" />
<br>
<img width="390" height="512" alt="image" src="https://github.com/user-attachments/assets/d62b6ed9-f7d3-4321-ba75-46a81c6441df" />
<br>

<img width="390" height="517" alt="image" src="https://github.com/user-attachments/assets/efd0b0fd-2f21-4386-b217-74edef27d75e" />
<br>
<img width="387" height="517" alt="image" src="https://github.com/user-attachments/assets/61ba0a3c-6882-457f-a6cb-abd3a6e65b4d" />
<br>
<img width="387" height="512" alt="image" src="https://github.com/user-attachments/assets/5c50900c-947a-4b7f-8710-d27b2b080248" />
<br>
<img width="620" height="512" alt="image" src="https://github.com/user-attachments/assets/529420ef-cd59-4fcf-939a-af69be0c7c41" />
<br>
<img width="490" height="507" alt="image" src="https://github.com/user-attachments/assets/4ecb554b-61aa-40a0-a95e-5868f5c085a8" />
<br>
<img width="391" height="516" alt="image" src="https://github.com/user-attachments/assets/a645888a-11b1-463e-8580-12d1142ce742" />
<br>
<img width="392" height="512" alt="image" src="https://github.com/user-attachments/assets/06afa3b1-20fd-4099-ac44-e9e7280b892c" />
<br>

## Result:
Thus, the images were read, displayed, brightness and contrast adjustments were made, and bitwise operations were performed successfully using the Python program.

