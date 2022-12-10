## Q1 A1 (15 points)
### Submission and rubrics:
- Brief explanation of your implementation.
  - <b> +7 </b>: Correct explanation: Linear solution (with SVD constrain enforcement).
  - <b> +5 </b>: Correct explanation but normalization missing.
  -  <b> +0 </b>:  Missing explanation.

- Epipolar lines: Show lines from fundamental matrix over the two images.
  - <b> +8 </b>: Correct epipolar lines.
  - <b> +4 </b>: Slightly incorrect epipolar lines.
  - <b> +0 </b>: No epipolar lines.


## Q1 A2 (5 points)
### Submission and rubrics:
- Brief explanation of your implementation.
  - <b> +2 </b>: Correct explanation, i.e. E = K'xFxK.
  - <b> +0 </b>: Missing explanation.
- Provide your estimated E
  - <b> +3 </b>: Correct E (within ballpark of our calculated E).
  - <b> +1 </b>: E off by a substantial factor (in the order of 1e3).
  - <b> +0 </b>: No E provided.


## Q1 B 7-point algorithm (20 points)
### Submission and rubrics:
- Brief explanation of your implementation.
  - <b> +10 </b>: Correct explanation.
  - <b> +0 </b>: Missing explanation.
- Epipolar lines: Show lines from fundamental matrix over the two images.
  - <b> +10 </b>: Correct epipolar lines.
  - <b> +5 </b>: Slightly incorrect epipolar lines.
  - <b> +2 </b>: Significant flaws in epipolar lines.
  - <b> +0 </b>: No epipolar lines.

## Q2 RANSAC (30 points)
### Submission and rubrics:
- Brief explanation of RANSAC implementation.
  - <b> +10 </b>: Explanation correctly stating the method of RANSAC. 
  - <b> +3 </b>: Part explanation of RANSAC. 
  - <b> +0 </b>: No explanation. 
- Epipolar lines: Show lines from fundamental matrix over the two images.
  - <b> +10 </b>: Correct epipolar lines. 
  - <b> +7 </b>: Slightly incorrect epipolar lines. 
  - <b> +3 </b>: Substantially incorrect epipolar lines. 
  - <b> +0 </b>: No epipolar lines. 
- Iterations vs. # of inliers via RANSAC
  - <b> +10 </b>: Correct plot showing 50-60 % of inliers reached for 7 point and 8 point. 
  - <b> +7 </b>: Slightly incorrect plot of inliers vs. iterations for 7 point and 8 point. 
  - <b> +2 </b>: Substantially incorrect plot of inliers vs. iterations for 7 point and 8 point. 
  - <b> +0 </b>: No plots. 


## Q3 Triangulation (30 points)
### Submission and rubrics:
- Brief explanation of triangulation implementation.
  - <b> +10 </b>: Explanation correctly stating linear solution of AX = 0. 
  - <b> +0 </b>: No explanation. 
- Pointcloud:
  - <b> +20 </b>: Correct pointcloud. 
  - <b> +15 </b>: No color in pointcloud. 
  - <b> +10 </b>: Inconsistency in pointcloud. 
  - <b> +0 </b>: No pointcloud. 


## Q4 Bonus 1: Bundle adjustment (10 points)
### Submission and rubrics:
- Brief explanation of bundle adjustment implementation.
  - <b> +5 </b>: Explanation correctly stating residual with least squares. 
  - <b> +0 </b>: No explanation. 
- Colored pointcloud after bundle adjustment:
  - <b> +5 </b>: Correct pointcloud display. 
  - <b> +3 </b>: Partially correct. 
  - <b> +0 </b>: No pointcloud. 


## Q5 Bonus 2: Fundamental matrix estimation on your own images. (10 points)
### Submission and rubrics:
- <b> +5 </b>: Brief explanation. 
- <b> +5 </b>: Correct epipolar lines. 
- <b> +0 </b>: Significant flaws in epipolar lines or no plot of epipolar lines.
