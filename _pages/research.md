---
permalink: /research/
layout: splash
title: <b>Main Research Topics in Our Lab</b>
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  excerpt: "Welcome to the Laboratory for Advanced BioMedical Imaging - Center for AI in Medical Imaging Research."
  overlay_image: /assets/images/projpic/bg_research.jpg
author_profile: false
carousels:
  - images: 
    - image: /assets/images/labpic/posterior_poi_partial.png
    - image: /assets/images/labpic/image2.png
    - image: /assets/images/labpic/tc_joined_CrI_no_bf.png
---

<style>
  .background {
  padding: 30px;
  box-sizing: border-box;
  border: 15px solid transparent;
  background-clip:padding-box;
  background-color: #e8d5b7;
  border-radius: 20px;
        }
.box {
  padding: 30px;
  box-sizing: border-box;
  border: 15px solid transparent;
  background-clip:padding-box;
  background-color: #e4e3dd ;
  border-radius: 50px;
  color: #000000;
  cursor: pointer;  
  transition: all 300ms;
  clear: both;
  height: 100px;
	-webkit-transition: line-height 1s, width 1s, height 1s, opacity 1s, border-radius 3s ,scale .5s, background-color 0.5s ease;
  transition: all 300ms;
        }
.box:hover {
    display: block;
    height: 550px;
    line-height:auto;
    scale:1.05;
    background-color:#f9b248;
    color: #F8F6F5;
}
.box a {
    display: none;
    font-size: 0.85em;
    text-align: left;
}
.box:hover a {
    display: block;
    }
.link-style {
  color:blue;
  /* margin-left: 1em;
  margin-right: 1em; */
  /* line-height: 1.5em; */

}

.link-style:hover {
    color:white;
    text-decoration: none;
}

.projimage{
    display: block;
    margin-left: auto;
    margin-right: auto;
} 
.box a:link { 
  text-decoration: none; 
} 
.box a:visited { 
  text-decoration: none; 
} 
.box a:hover { 
  text-decoration: none; 
} 
.box a:active { 
  text-decoration: none; 
}

.galleryItem {
  padding: 30px;
  box-sizing: border-box;
  border: 15px solid transparent;
  background-clip:padding-box;
  background-color: #e4e3dd ;
  border-radius: 50px;
  color: black;
  cursor: pointer;  
  transition: all 300ms;
  clear: both;
  height: 140px;
	-webkit-transition: line-height 1s, height .5s, opacity 1s, border-radius 3s ,scale .5s;

}
.galleryItem:hover {
    display: block;
    background-color: #edece4 ;
    height:400px;
    line-height:auto;
    scale:1.05;
}
.galleryItem ul {
    display: none;
    font-size: 0.9em;
    line-height: 1.5em;
}
.galleryItem:hover ul {
    display: block;
    }
.text {
margin-left: 1.5em;
margin-right: 1.5em;
font-size: 0.9em;
}

</style>
<div class="container">
  <div class="row">
    <div class="col-md-1" >
    </div>
    <div class="col-md-10 background" >
      <!--{% include carousel.html height="5" unit="%" duration="7" number="1" %}-->
      <h4 style="text-align:center"><b>Research Topics </b></h4>
      <div class="text"> 
        <p> 
        Our lab is a part of Center for Artificial Intelligence in Medical Imaging Research at Chonnam National University Hospital. We have access to patient medical imaging data, including magnetic resonance imaging (MRI), computerized tomography (CT), x-rays, mammography and ultrasound, as well as patient EMR (electronic medical record) data, which have been utilized to build machine learning/deep learning models for detection, diagnosis, and prediction of various diseases as well as prediction of therapy response. 
        </p>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-md-6" >
            <div class="galleryContainer">
              <div class="galleryItem">
                <h6 style="text-align:center"> <b>Machine learning and deep learning for clinical application </b></h6>
                <ul>
                  <li>Start Deep Learning Research as a Radiologist</li>
                  <li>Apply machine learning and deep learning for solving clinical questions</li>
                  <li>Automatic classification of diseases using various medical imaging modalities</li>
                  <li>Python and Deep Learning Bootcamp</li>
                </ul>
              </div>  
            </div>
          </div>
          <div class="col-md-6">
            <div class="galleryContainer">
              <div class="galleryItem">
                <h6 style="text-align:center"> <b>Hyperpolarized carbon-13 MRI</b></h6>
                <ul >
                  <li>What is Hyperpolarized (HP) imaging?</li>
                  <li>Relevance of HP C-13 MRI</li>
                  <li>Pyruvate metabolism</li>
                  <li>Application of HP C-13 MRI in pre-clinical models</li>
                  <li>Application of HP C-13 MRI in clinical study</li>
                </ul>
              </div>
            </div>
          </div>
        </div> 
      </div>
      <div class="container">
        <h4 style="text-align:center"><b>Ongoing Projects</b></h4>
        <div class="Text"><p>For more information click on the projects</p></div>
        <div class="row">
          <div class="col-md-6">
            <div class="galleryContainer">
              <div class="galleryItem">
                <h5 style="text-align:center">  <b>Kidney</b> </h5>
                <ul >
                  <li>JD 1</li>
                  <li>JD 2</li>
                  <li>JD 3</li>
                  <li>JD 4</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="galleryContainer">
              <div class="galleryItem">
                <h5 style="text-align:center">  <b>Stroke</b> </h5>
                <ul >
                  <li>JD 1</li>
                  <li>JD 2</li>
                  <li>JD 3</li>
                  <li>JD 4</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="galleryContainer">
              <div class="galleryItem"> 
                <a href="https://github.com/cnuradiology/MeningiomaRadiomics"  class="link-style">
                  <h5 style="text-align:center"> <b>Meningioma</b></h5>
                </a>
                <ul >
                  <li>JD 1</li>
                  <li>JD 2</li>
                  <li>JD 3</li>
                  <li>JD 4</li>
                </ul>
                <!-- <a href="https://gepris.dfg.de/gepris/projekt/510229904"  class="link-style">
                  The DRhyaDS project ("Dekodierung der dynamischen Rhythmen von Sprache") crosses disciplinary boundaries between speech signal processing, psycholinguistics and cognitive neuroscience  neuroscience and advances both 
                  theoretical foundations of successful speech perception as well as the best practices
                  practices of spontaneous speech analysis.  <br><br>
                  DFG Research Unit For 510229904
                </a> -->
              </div>
            </div>
          </div>  
        </div>
      </div>
      <br>
      <h4 style="text-align:center"> <b>Open Science Commitment</b></h4>
      <div class="text"><p>
        At our lab, we uphold a steadfast commitment to open and fair science. We believe that transparency and integrity are fundamental to the advancement of knowledge and the betterment of society. Through open collaboration, rigorous methodologies, and equitable practices, we strive to ensure that our research contributes meaningfully to the scientific community and promotes inclusivity and accessibility for all.
      </p> </div>
    </div>
  </div>
</div>
<br>