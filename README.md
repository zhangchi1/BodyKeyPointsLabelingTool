# BodyKeyPointsLabelingTool
## A simple web based labeling tool allows user to upload an image, click the 13 body key points and download the body key points coordinates as a text file.
## 13 key-points: 0. head, 1. left shoulder, 2. right shoulder, 3. left elbow, 4. right elbow, 5. left wrist, 6. right wrist, 7. left hip, 8. right hip, 9. left knee, 10. right knee, 11. left ankle, 12. right ankle

### Instructions:
1. Click choose file button to upload an image.
2. Click body key points on the top image, the X and Y coordinates are shown at the bottom:
  *  0, 0, x:261, y:301
  *  0, 1, x:324, y:307
  where 0 (person index 0), 0 (body point index 0 represents head), x:261 (x coordinate of the head), y:301 (y coordinate of the head)
3. Input s key to skip to the next body key point, if the current body point is not available in the image, X and Y coordinates will return x:N/A, y:N/A.
4. Input d key to delete the last body key point.
5. Click save button then click download button to download those body key points as a txt file.
