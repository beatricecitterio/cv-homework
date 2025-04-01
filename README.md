Group homework for Computer Vision and Image Processing (20878), done by Beatrice Citterio, Clara Montemurro and Martina Serandrei.

The homework cons
1) **Single view metrology**
Implement an algorithm capable of estimating a person’s height from a single image. The image
must include a person whose height is unknown and a reference object (such as another person)
with a known height.
Specifically, capture an image of two people, A and B, standing on the same horizontal plane. A
and B must be in general position with respect to the camera. Assume that the height of person A
is known and estimate the height of person B by leveraging only on projective geometry. When
acquiring the image, ensure that your image contains sufficient geometric cues to facilitate the
estimation.

3) **The eight point algorithm**
Implement the eight-point algorithm and test it on a pair of images that you have captured
yourself. You can either use SIFT with robust fitting to extract correspondences or manually
annotate the images (a minimum of 10 correspondences is sufficient).
Estimate the fundamental matrix F using your algorithm and visualize the results by plotting all
the epipolar lines in the first image. Use a geometric error to assess how well your estimate
describe the epipolar geometry.
