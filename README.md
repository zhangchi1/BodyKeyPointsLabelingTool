# BodyKeyPointsLabelingTool
## A simple web based labeling tool allows user to upload an image, click the 13 body key points and download the body key points coordinates as a text file.
## 13 key-points: 0. Head, 1. Left shoulder, 2. Left elbow, 3. Left wrist, 4. Left hip, 5. Left knee, 6. Left ankle, 7. Right shoulder, 8. Right elbow, 9. Right wrist, 10. Right hip, 11. Right knee, 12. Right ankle
### Instructions:
1. Click choose file button to upload an image.
2. Click body key points on the top image, the X and Y coordinates are shown at the bottom:
  *  0, 0, x:261, y:301
  *  0, 1, x:324, y:307
  where 0 (person index 0), 0 (body point index 0 represents head), x:261 (x coordinate of the head), y:301 (y coordinate of the head)
3. Input s key to skip to the next body key point, if the current body point is not available in the image, X and Y coordinates will return x:N/A, y:N/A.
4. Input d key to delete the last body key point.
5. Click save button to save your current body key points and download those body key points as a txt file.
