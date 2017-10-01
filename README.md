# algorithms-project1
## 1. Overview
In this project, you will implement a Harris Corner Detector. This project will help you understand eigenvalue decomposition, convolution, morphological operations, and non-maximum supression.

## 2. The Harris Corner Detector
Your implementation of Harris corner detector should follow ["A combined corner and edge detector"](http://www.bmva.org/bmvc/1988/avc-88-023.pdf) [1] by C J Harris very closely. You may find [these](https://baf05b94-a-ab15346e-s-sites.googlegroups.com/a/umich.edu/eecs442-winter2015/442-lec07-edges-corners.pdf?attachauth=ANoY7com5VoZiyhlBYaInK1B9QaOHR7LMUzg1_sy52MuQFE8Q9ci6dXnNu51XfHPgjHr4DKTu7ytekAneeG_hTfJH59Y57whS3rc0BMOLZr90ch1rRxYjwRbcvx3fJMigexK3-ZOD-pyN9rpAf3SIVuWPXYdLn9XTi58eilQTiNBx2iGvFVAJQHMm6S_pSN6GuN74A2y9gfzXpITh83653MbdHsPUSwO_JoLB7skfUvntAFT-Uctk5Q%3D&attredirects=0) slides from EECS 442 helpful. More details regarding the algorithm will be covered in a later seminar.

## 3. Logistics
 * You should implement the harris corner detector to find both corners and points belonging to an edge. (We know this is no where near the state-of-the-art edge detector)
 * It is okay to have threholds hard coded or passed in as an argument.
 * You may not use `cornerHarris` function from the `OpenCV` Library.
 * You should find the second moment matrix using convolution.
 * You should implement a 2 by 2 EVD to find the corner response function (Just the eigenvalues are sufficient for this project).
 * You should implement your own non-maximal supression [Hint: what is the relation between a dialation and max filter?].
 * We do not plan to release any starter code.

## 4. References
[1]  C. Harris and M.J. Stephens. A combined corner and edge detector. In _Alvey Vision Conference_, pages 147 - 152, 1988.

