# Image Guide for Door Detection Tutorial

## 📸 Required Images Checklist

This guide helps you find or create all the images needed for your tutorial.

## Main Tutorial Images (18 images)

### Homepage & Problem Section (3 images)

1. **door-detection-hero.jpg**
   - **What:** Mobile phone detecting a door with bounding box overlay
   - **Where to find:** 
     - Search Unsplash: "smartphone camera door"
     - Create: Take photo of door, add bounding box in PowerPoint/Photoshop
   - **Alternative:** Person using phone to navigate indoors

2. **indoor-navigation.jpg**
   - **What:** Person with low vision navigating indoor hallway
   - **Where to find:**
     - Search Pexels: "person walking hallway" or "blind person cane"
     - Stock photo sites with accessibility themes
   - **Alternative:** Empty hallway showing navigation challenge

3. **low-vision-user.jpg**
   - **What:** Low vision user with smartphone using door detection app
   - **Where to find:**
     - Search: "person using smartphone accessibility"
     - Create: Stage photo with friend using phone
   - **Alternative:** Close-up of hands holding phone with app interface

### Sensors Section (2 images)

4. **rgb-camera-detection.jpg**
   - **What:** RGB camera view with detected door highlighted
   - **Where to find:**
     - Take photo of door, add colored bounding box in image editor
     - Screenshot from YOLO demo videos on YouTube
   - **Alternative:** Diagram showing camera → door detection pipeline

5. **depth-sensor-comparison.jpg**
   - **What:** Side-by-side: RGB image vs. depth map
   - **Where to find:**
     - Search: "RGB-D depth map comparison"
     - Use iPhone LiDAR scanner apps (3D Scanner App)
     - Research papers on depth sensing
   - **Alternative:** Create diagram showing RGB vs depth concept

### Classical Methods Section (4 images)

6. **edge-detection-steps.jpg**
   - **What:** 4-panel showing: (a) Original, (b) Edges, (c) Lines, (d) Detected door
   - **How to create:**
     - Use OpenCV in Python to process a door image
     - Save each step, combine in PowerPoint
   - **Code example:**
     ```python
     import cv2
     img = cv2.imread('door.jpg')
     gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
     edges = cv2.Canny(gray, 50, 150)
     cv2.imwrite('edges.jpg', edges)
     ```

7. **vanishing-point.jpg**
   - **What:** Hallway with lines converging to vanishing point
   - **Where to find:**
     - Search: "hallway perspective vanishing point"
     - Take photo of long hallway
     - Add lines in PowerPoint pointing to vanishing point
   - **Alternative:** Diagram illustrating vanishing point concept

8. **handle-detection.jpg**
   - **What:** Close-up of door handle with detection box
   - **Where to find:**
     - Take photo of door handle
     - Add green bounding box in image editor
   - **Alternative:** Diagram showing handle as key feature

9. **use-case-diagram.jpg**
   - **What:** Diagram showing door detection scenarios
   - **How to create:**
     - Use draw.io or PowerPoint
     - Show: Hospital, University, Mall scenarios
     - Add icons and arrows
   - **Alternative:** Collage of different door types

### Learning Methods Section (3 images)

10. **yolo-architecture.jpg**
    - **What:** YOLOv8 architecture diagram
    - **Where to find:**
      - Ultralytics documentation: https://docs.ultralytics.com
      - Research papers on YOLO
      - Create simplified version in PowerPoint
    - **Alternative:** Generic CNN architecture diagram

11. **mobile-architectures.jpg**
    - **What:** Graph comparing accuracy vs. speed for different models
    - **How to create:**
      - Use Excel or Google Sheets
      - Plot: MobileNet, YOLO, EfficientDet
      - Export as image
    - **Alternative:** Table comparing model specifications

12. **3d-understanding.jpg**
    - **What:** 3D door pose estimation showing swing direction
    - **Where to find:**
      - Search: "3D object detection visualization"
      - Create: Draw door with 3D coordinate axes in PowerPoint
    - **Alternative:** Diagram showing door orientation angles

### Evaluation Section (3 images)

13. **success-wooden-door.jpg**
    - **What:** Wooden door with high-confidence detection (green box, 98%)
    - **How to create:**
      - Take photo of wooden door
      - Add green bounding box with "98%" label
    - **Alternative:** Stock photo of standard door

14. **success-hallway.jpg**
    - **What:** Multiple doors detected in hallway scene
    - **Where to find:**
      - Take photo of hallway with multiple doors
      - Add multiple bounding boxes
    - **Alternative:** Diagram showing multi-door detection

15. **failure-glass-door.jpg**
    - **What:** Glass door that detector missed (only frame detected)
    - **How to create:**
      - Take photo of glass door
      - Add partial/failed detection box
    - **Alternative:** Photo of glass door with "Not Detected" label

16. **failure-occlusion.jpg**
    - **What:** Door with person blocking lower portion
    - **Where to find:**
      - Stage photo with friend in front of door
      - Search: "person standing doorway"
    - **Alternative:** Diagram showing occlusion problem

### Challenges & Future Sections (3 images)

17. **door-diversity.jpg**
    - **What:** 4-panel showing different door types: Office, Hospital, Residential, Mall
    - **How to create:**
      - Take photos of different door types
      - Combine in PowerPoint grid
    - **Alternative:** Collage from stock photos

18. **edge-cases.jpg**
    - **What:** 4-panel: Revolving door, Sliding door, Curtain door, Camouflaged door
    - **Where to find:**
      - Search each type individually
      - Visit mall/airport for revolving/sliding doors
    - **Alternative:** Diagrams illustrating each type

19. **multimodal-fusion.jpg**
    - **What:** Diagram showing RGB + Depth + IMU fusion
    - **How to create:**
      - Use draw.io or PowerPoint
      - Show sensors → fusion → detection
      - Add icons for each sensor
    - **Alternative:** Flowchart of sensor integration

## Quiz Images (4 images)

20. **quiz-wooden-door.jpg**
    - **What:** Clear wooden door, frontal view
    - **Where to find:** Take photo or use stock image

21. **quiz-glass-door.jpg**
    - **What:** Transparent glass door
    - **Where to find:** Mall, office building, or stock photo

22. **quiz-occluded.jpg**
    - **What:** Door with person/object blocking part of it
    - **Where to find:** Stage photo or search stock images

23. **quiz-window.jpg**
    - **What:** Tall window that could be confused with door
    - **Where to find:** Take photo or search "floor to ceiling window"

## 🎨 Image Creation Tools

### Free Photo Editing
- **GIMP** (free Photoshop alternative): https://www.gimp.org/
- **Paint.NET** (Windows): https://www.getpaint.net/
- **Photopea** (online, Photoshop-like): https://www.photopea.com/

### Diagram Creation
- **draw.io** (free, online): https://app.diagrams.net/
- **Canva** (free tier): https://www.canva.com/
- **PowerPoint** (if you have Office)
- **Google Slides** (free)

### Adding Bounding Boxes
1. Open image in any editor
2. Use rectangle tool
3. Set no fill, colored border (green for success, red for failure)
4. Add text label with confidence score
5. Export as JPG

### Stock Photo Sources
- **Unsplash:** https://unsplash.com/ (free, high quality)
- **Pexels:** https://pexels.com/ (free, no attribution required)
- **Pixabay:** https://pixabay.com/ (free)
- **Wikimedia Commons:** https://commons.wikimedia.org/ (free, check licenses)

## 📐 Image Specifications

- **Format:** JPG or PNG
- **Size:** 800-1200px width recommended
- **File size:** Keep under 500KB each for fast loading
- **Aspect ratio:** 16:9 or 4:3 works well

## 🔍 Search Keywords

Use these keywords when searching stock photo sites:

- "door hallway perspective"
- "smartphone camera detection"
- "person using accessibility app"
- "indoor navigation blind"
- "glass door entrance"
- "wooden door handle"
- "hallway vanishing point"
- "depth sensor visualization"
- "mobile phone AI"

## ✅ Quick Checklist

Before submitting, verify:

- [ ] All 23 images are in the `images/` folder
- [ ] File names match exactly (case-sensitive!)
- [ ] Images are properly sized (not too large)
- [ ] Each image has a clear purpose
- [ ] Images are properly cited if borrowed

## 💡 Pro Tips

1. **Consistency:** Use similar style/quality for all images
2. **Clarity:** Make sure text/diagrams are readable
3. **Attribution:** If using others' images, cite in caption
4. **Compression:** Use TinyPNG.com to reduce file sizes
5. **Testing:** View images on both desktop and mobile

## 🚀 Fastest Approach

**Minimum viable images (if short on time):**

1. Take 5 photos of different doors with your phone
2. Add colored rectangles (bounding boxes) in PowerPoint
3. Export slides as images
4. Create 2-3 simple diagrams in PowerPoint
5. Search stock photos for the rest

**Time estimate:** 1-2 hours total

## 📧 Need Help?

If you're stuck finding/creating images:
- Ask classmates to share resources
- Check course discussion board
- Email instructor for guidance
- Use simple diagrams instead of photos

---

**Remember:** Images enhance understanding but don't need to be perfect. Clear, relevant visuals are more important than professional photography!

