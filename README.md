```
# Define our imshow function 
def imshow(title = "Image", image = None, size = 10):
    w, h = image.shape[0], image.shape[1]
    aspect_ratio = w/h
    plt.figure(figsize=(size * aspect_ratio,size))
    plt.imshow(cv2.cvtColor(image, cv2.COLOR_BGR2RGB))
    plt.title(title)
    plt.show()
```
### Grab Cut Algorithm
<img width="589" alt="Screenshot 2023-05-13 at 4 06 45 PM" src="https://github.com/ayushs0911/OpenCV/assets/122048067/73c5af4d-bb3c-4b3d-8d76-6a2fe9a9e5bf">

### OCR
<img width="543" alt="Screenshot 2023-05-13 at 4 05 54 PM" src="https://github.com/ayushs0911/OpenCV/assets/122048067/72a4d823-91c8-4f13-9f84-711368a760ed">

### Face Detection using HaarCascade Classifier
![Screen_Recording_2023-05-13_at_3_48_05_PM_AdobeExpress](https://github.com/ayushs0911/OpenCV/assets/122048067/794676da-890c-4716-864b-c090b0d068d1)
