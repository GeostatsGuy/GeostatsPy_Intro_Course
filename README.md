<p>
    <img src="https://github.com/GeostatsGuy/GeostatsPy/blob/master/TCG_color_logo.png?raw=true" width="220" height="200" />
</p>

# Open Source Spatial Data Analytics in Python with [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy), Short Course

### by Michael Pyrcz, Associate Professor, The University of Texas at Austin

___

This course provides an introduction to GeostatsPy, an open source Python package for Spatial / Subsurface Data Analytics and Geostatistics, with fundamental spatial data analytics concepts in lectures followed by interactive demonstrations/exercises and more complete example well-documented worklfows.

___

**Before Attending the Course Please Install the Following**:
 
1. Anaconda 3.*
2. GeostatsPy package

For more details see below.

___

I have included in this repository all of the course content:

1. the lectures as PDFs in the [Lectures](https://github.com/GeostatsGuy/GeostatsPy_Intro_Course/tree/master/Lectures) folder

2. the well-documented and interactive demonstration workflows in Python in the [Workflows](https://github.com/GeostatsGuy/GeostatsPy_Intro_Course/tree/master/Workflows) folder

3. datasets required for the workflows in the [Datasets](https://github.com/GeostatsGuy/GeostatsPy_Intro_Course/tree/master/DataSets) folder

#### Course Objectives:

You will gain:

* knowledge concerning basics of the use of the GeostatsPy package for spatial/subsurface data analytics and geostatistics in Python. 

* experience with a variety of practical spatial data analytics / geostatistics workflows in Python

#### Course Agenda

The short course is broken up into 5 sections, including:

0. **Introduction**: objectives, plan
1. **Variogram Calculation**: quantifying spatial continuity
2. **Variogram Modeling**: formulating valid spatial continuity models
3. **Kriging**: spatial estimation
4. **Conclusions**: summary and feedback

#### Getting Started

Here's the steps to get setup locally with Anaconda for Python 3.\*, common Python packages, Jupyter Notebooks and the GeostatsPy package:

1. Install [Anaconda 3](https://www.anaconda.com/products/individual). 
2. From Anaconda Navigator (within Anaconda3 group), go to the environment tab, click on base (root) green arrow and open a terminal. 
3. In the terminal type: `pip install geostatspy statsmodels` and `conda install pandas numpy scipy matplotlib jupyter`. 
4. Navigate to where you unzipped or cloned the GitHub repository with the `cd` command (eg: `cd C:\Users\Joe\Documents\GitHub\GeostatsPy_Intro_Course`)
5. Then start a notebook by typing `jupyter notebook`. The notebook control panel will open in your browser.
6. Open Jupyter Notebook and in the top block get started by copy and pasting the code block below from this Jupyter Notebook to start using the geostatspy functionality. 

```python
import geostatspy.GSLIB as GSLIB
import geostatspy.geostats as geostats
```

For more information about about the GeostatsPy package check out the [documentation](https://github.com/GeostatsGuy/GeostatsPy) and [code](https://github.com/GeostatsGuy/GeostatsPy/tree/master/geostatspy). 

You will need to copy these data files to your working directory.  They are available in the [DataSets](https://github.com/GeostatsGuy/GeostatsPy_Intro_Course/tree/master/DataSets) folder of this repository:

* [sample_data_MV_biased,csv](https://github.com/GeostatsGuy/GeostatsPy_Intro_Course/blob/master/DataSets/sample_data_MV_biased.csv)

* [sample_data_biased.csv](https://github.com/GeostatsGuy/GeostatsPy_Intro_Course/blob/master/DataSets/sample_data_biased.csv)

#### The Instructor:

### Michael Pyrcz, Associate Professor, University of Texas at Austin 
*Novel Data Analytics, Geostatistics and Machine Learning Subsurface Solutions*

With over 17 years of experience in subsurface consulting, research and development, Michael has returned to academia driven by his passion for teaching and enthusiasm for enhancing engineers' and geoscientists' impact in subsurface resource development. 

For more about Michael check out these links:

#### [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)

#### Want to Work Together?

I hope that this is helpful to those that want to learn more about subsurface modeling, data analytics and machine learning. Students and working professionals are welcome to participate.

* Want to invite me to visit your company for training, mentoring, project review, workflow design and consulting, I'd be happy to drop by and work with you! 

* Interested in partnering, supporting my graduate student research or my Subsurface Data Analytics and Machine Learning consortium (co-PIs including Profs. Foster, Torres-Verdin and van Oort)? My research combines data analytics, stochastic modeling and machine learning theory with practice to develop novel methods and workflows to add value. We are solving challenging subsurface problems!

* I can be reached at mpyrcz@austin.utexas.edu.

I'm always happy to discuss,

*Michael*

Michael Pyrcz, Ph.D., P.Eng. Associate Professor The Hildebrand Department of Petroleum and Geosystems Engineering, Bureau of Economic Geology, The Jackson School of Geosciences, The University of Texas at Austin

#### More Resources Available at: [Twitter](https://twitter.com/geostatsguy) | [GitHub](https://github.com/GeostatsGuy) | [Website](http://michaelpyrcz.com) | [GoogleScholar](https://scholar.google.com/citations?user=QVZ20eQAAAAJ&hl=en&oi=ao) | [Book](https://www.amazon.com/Geostatistical-Reservoir-Modeling-Michael-Pyrcz/dp/0199731446) | [YouTube](https://www.youtube.com/channel/UCLqEr-xV-ceHdXXXrTId5ig)  | [LinkedIn](https://www.linkedin.com/in/michael-pyrcz-61a648a1)
