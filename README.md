# Plantae-seminar-Nov2018

Author: Amy Tabb.  Questions/comments/problems: amy.tabb@ars.usda.gov

A repository with notes from the seminar given on 28 November 2018.  This repository will be updated over time, so suggest you check back at the source if there is an issue.  

*Last updated: 1 December, 2018*

The webinar recording is posted on [Plantae, ASPB](https://community.plantae.org/video/5127327460051912557/transforming-pixels-to-millimeters-geometric-camera-calibration).

The presentation is a .pdf that is 100MB, and it, and the accompanying videos are stored on Google Drive.  If you are not able to access this, let me know and we will find a workaround.

[Presentation](https://drive.google.com/open?id=1W2bh93AwjBnOoulAcmfpS9RwNG19PHQ9) 

[Video 1, page 5 ](http://www.coviss.org/tabbmedeiros_rotse_iros17/)

[Video 2, page 11 ](https://drive.google.com/open?id=1kz28A8QdtMzH0Hc2D-qWXs6W25mXYy8M)

[Video 3, page 56 ](https://drive.google.com/open?id=14DoJfhXRWG_HfYUuaw5Ef2sj1bH-vnOh)

(Thursday: I believe with Okular, and downloading the .pdf, the videos will play on Ubuntu, but I have not tested this.  They will not play on Windows.)

Tabb and Medeiros citation is:

A. Tabb and H. Medeiros, "A robotic vision system to measure tree traits," 2017 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Vancouver, BC, 2017, pp. 6005-6012. doi: 10.1109/IROS.2017.8206497
* [Publisher](https://ieeexplore.ieee.org/document/8206497)
* [arXiv](https://arxiv.org/pdf/1707.05368.pdf)
* [video](http://www.coviss.org/tabbmedeiros_rotse_iros17/)

### MVG
MVG, or **Multiple View Geometry in Computer Vision**, by Richard Hartley and Andrew Zisserman. ISBN: 0521540518
* [Website](http://www.robots.ox.ac.uk/~vgg/hzbook/) 

Another camera calibration reference for more in-depth details, very much beyond the scope of this talk, is Zhengyou Zhang's [technical report](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr98-71.pdf) on Camera calibration. Other versions are the [TPAMI version](https://ieeexplore.ieee.org/document/888718). As I understand it, before this time more expensive and precise two- and three-plane calibration objects were used, so this technique really changed the field.  Unbelievably, this tech report is now 20 years old!

### OpenCV

[OpenCV](https://opencv.org/), or Open Computer Vision.

[OpenCV camera calibration tutorial, version 3.0, C++](https://docs.opencv.org/3.1.0/d4/d94/tutorial_camera_calibration.html)


### Examples of plant phenotyping papers that use measurement from images:

* S. Heckwolf, M. Heckwolf, S. M. Kaeppler, N. de Leon, and E. P. Spalding, “Image analysis of anatomical traits in stalk transections of maize and other grasses,” Plant Methods, vol. 11, no. 1, p. 26, Apr. 2015. [Open access paper](https://plantmethods.biomedcentral.com/articles/10.1186/s13007-015-0070-x)

* Z. Migicovsky, M. Li, D. H. Chitwood, and S. Myles, “Morphometrics Reveals Complex and Heritable Apple Leaf Shapes,” Front. Plant Sci., vol. 8, 2018.
[Open access paper](https://www.frontiersin.org/articles/10.3389/fpls.2017.02185/full)

* M. Müller-Linow, F. Pinto-Espinosa, H. Scharr, and U. Rascher, “The leaf angle distribution of natural plant populations: assessing the canopy with a novel software tool,” Plant Methods, vol. 11, no. 1, p. 11, Feb. 2015. [Open access paper](https://plantmethods.biomedcentral.com/articles/10.1186/s13007-015-0052-z)

### Rolling shutter

Figure from [Wikipedia](https://en.wikipedia.org/wiki/Rolling_shutter). 

Good explanation and video from [DIY Photography](https://www.diyphotography.net/everything-you-wanted-to-know-about-rolling-shutter/).

### Camera calibration code

Code for calibrating your own camera with a chessboard-style pattern is available in another repository, [basic-chessboard-cali](https://github.com/amy-tabb/basic-chessboard-cali).

If you are using a consumer-style camera, make sure that only one focal length is used, also known as, turn auto focus off.  

A chessboard is included in this repository (Chessboard.png); many more are avaliable online.  This one has 15 corners in the vertical direction, and 10 in the horizontal direction.  I have had great success in ordering prints of the patterns on a low-gloss alumnium, which is then durable and washable (and comes with its own frame!), for field and greenhouse conditions.  I always encourage people to test with the cheapest thing first (i.e., paper), and do not want to endorse any product, but a web search of "metal or aluminum image print" or similar will probably find you something in your region.

### Camera obscura reference:

“Camera Obscura Image of Manhattan View Looking West in Empty Room," by Aberlardo Morell. copyright 1996, Smithsonian American Art Museum [link](http://edan.si.edu/saam/id/object/1998.159)

### Maize figure:
Dzievit, Matthew (2018): Maize-Mo17 - Full plant at flowering with correct leaf angles.png. figshare. Figure. [doi: 10.6084/m9.figshare.6994376.v1](https://doi.org/10.6084/m9.figshare.6994376.v1)

### 3-Demeter tool:

[Github:thsant/3dmcap](https://github.com/thsant/3dmcap)
Citation: Santos, T. T., Bassoi, L. H., Oldoni, H., & Martins, R. L. (2017). Automatic grape bunch detection in vineyards based on
affordable 3D phenotyping using a consumer webcam. In J. G. A. Barbedo, M. F. Moura, L. A. S. Romani, T. T. Santos, & D. P.
Drucker (Eds.), Anais do XI Congresso Brasileiro de Agroinformática (SBIAgro 2017) (pp. 89 - 98). Campinas: Unicamp.


### arUco tags 
S. Garrido-Jurado, R. Muñoz-Salinas, F. J. Madrid-Cuevas, and M. J. Marín-Jiménez, “Automatic generation and detection of highly reliable fiducial markers under occlusion,” Pattern Recognition, vol. 47, no. 6, pp. 2280–2292, Jun. 2014. 
[Publisher](https://www.sciencedirect.com/science/article/abs/pii/S0031320314000235)  [OpenCV documentation](https://docs.opencv.org/3.1.0/d5/dae/tutorial_aruco_detection.html)

Note that the *aruco* library is included in the contributed module of OpenCV, which is where extra, experimental modules are housed before they are incorporated into the main release of OpenCV.  You can read more about the contributed module at its [Github repository](https://github.com/opencv/opencv_contrib).

### Shape from Motion (SfM) and EXIF tags

[Changchang Wu's VisualSFM](http://ccwu.me/vsfm/doc.html#basic)

[Noah Snavely's Bundler](http://www.cs.cornell.edu/~snavely/bundler/)

### Camera as a scanner

Code and technical report to be announced.  To you want to be notified?  Please email with the subject "camera as scanner request".  I'll send out a notice when it is ready.

Original and result files from this portion of the talk are included in this repository.  `iphone6` holds the original images, and then `iphone6_results` has the results.  Interpreting the results files:
* `internal_initial_detectN.jpg` is the original image with the coordinates of the detected world coordinate system overlaid on the image.  If a n arUco tag was detected, it will be outlined in cyan and have a small magenta number in the center. 
* `undistortedN.jpg` has the undistorted version of the original image, using the calibration information.
* `warpedN.jpg` is the image after the homography to transform it into the world coordinate system coordinates has been estimated, and applied.  The units are 10 pixels = 1mm.
* `croppedN.jpg` is a cropped version of `warpedN.jpg` that is 1550x2060 pixels.  To print to scale, print at 155x206mm.

### Related organizations and conferences

IEEE Robotics and Automation Society's Technical Committee on Agricultural Robotics and Automation: [ieeeagra.com](http://ieeeagra.com/)

[Phenome 2019, February 6-10, 2019](http://phenome2019.org/)
http://phenome2019.org/




