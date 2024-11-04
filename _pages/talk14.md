---
layout: talk
title: "Generic Interactive Pixel-level Image Editing"
permalink: /Speech/talk14/
---

<div class="talk-container">
    <div class="talk-header">
        <h2>Presenter: Prof. Yun Liang</h2>
    </div>

    <h3>Abstract</h3>
    <p>
    Several image editing methods have been proposed in the past decades, achieving brilliant results. The most sophisticated of them, however, require additional information per-pixel. For instance, dehazing requires a specific transmittance value per pixel, or depth of field blurring requires depth or disparity values per pixel. This additional per-pixel value is obtained either through elaborated heuristics or through additional control over the capture hardware, which is very often tailored for the specific editing application. In contrast, however, we propose a generic editing paradigm that can become the base of several different applications. This paradigm generates both the needed per-pixel values and the resulting edit at interactive rates, with minimal user input that can be iteratively refined. Our key insight for getting per-pixel values at such speed is to cluster them into superpixels, but, instead of a constant value per superpixel (which yields accuracy problems), we have a mathematical expression for pixel values at each superpixel: in our case, an order two multinomial per superpixel. This leads to a linear least squares system, effectively enabling specific per-pixel values at fast speeds. We illustrate this approach in three applications: depth of field blurring (from depth values), dehazing (from transmittance values) and tone mapping (from brightness and contrast local values), and our approach proves both favorably interactive and accurate in all three. Our technique is also evaluated with a common dataset and compared favorably.
    </p>

    <h3>Biography</h3>
    <p>
    Yun Liang is a professor at the College of Mathematics and Informatics in the South China Agricultural University (SCAU). She received her Bachelor degrees from Shan Dong Agricultural University, China, in 2003, and her PhD and Master degree in Computer Science & Engineering from the Sun Yat-Sen University in 2011 and 2005 respectively. She has visited Simon Fraser University under the supervisor Professor Ping Tan from 2016 to 2017.
    </p>
    <p>
    Her research interest keywords are computer vision, computer graphics, robotics, master agriculture and so on. She has published more than fifty papers on PG, ECCV, TMM, TVCG, PR, Signal Processing and so on. One paper has been awarded the First prize of Excellent Thesis Award of Guangdong Computer Society. She has won the Second prize of science and technology progress award of China Image Graphics Society. She has finished some research projects including the National Natural Science Fund, the Science and Technology Planning Project of Guangdong Province and so on. She has obtained nine authorized patents and twenty-five authorized software copyrights.
    </p>
</div>
