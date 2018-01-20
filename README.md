# Data Analysis in Python
Python is a general purpose easy to learn language having a flat learning curve. The syntax is relatively simple. The language can be easily understood and learnt by statisticians. Even with the knowledge of the syntax and basic functionality, one can start off with learning to use the Python libraries developed specifically for the purpose of data analysis.

## Packages required for Data Analysis
* ### NumPy
It is one of the fundamental packages used for scientfic computing and data analysis. Its most important feature is the powerful N-dimensional array object. Vectorization makes these these libraries a speedy tool while analyzing data. A thorough knowledge of NumPy forms a good base for learning the Pandas library.

[NumPy Documentation](http://www.numpy.org/)

* ### Pandas
Pandas is an open source library built on top of NumPy. It provides high-performance data analysis tools and easy-to-use data structures such as Series and DataFrame for the Python programming language.

[Pandas Documentation](http://pandas.pydata.org/pandas-docs/stable/10min.html)

* ### Matplotlib
This library enables the user to produce publication quality figures. The analysis carried out using NumPy and Pandas can be depicted in a pictographic form using the Matplotlib library.

[Matplotlib Documentation](https://matplotlib.org/)

* ### Bokeh
Bokeh is an interactive data visualization library. It enables to create elegant and concise plot effortlessly. Personally, I felt more at ease while using Bokeh as compared to Matplotlib especially because of it's lucid and to-the-point documentation.

[Bokeh Documentation](https://bokeh.pydata.org/en/latest/docs/user_guide/quickstart.html)

## Installation of Packages
There are quite a few ways to install the required packages for data analysis, but the easiest way is with Anaconda. It is a cross-platform (Linux, Mac OS X, Windows) Python distribution for data analytics and scientific computing. Anaconda makes it easy to install-:

* Core Python language
* Python packages (libraries)
* Spyder IDE
* Jupyter Notebook
* Anaconda's package manager- conda (used for updating Anaconda and packages)

#### Download
**NOTE:** Choose the Python 3x version Graphical Installer
[Anaconda Download Link](https://www.anaconda.com/download/)

* Run the Anaconda setup.
* Once completed, all the required packages will have been installed.
* Run the Anaconda Prompt.

**NOTE:** In case Bokeh isn't pre installed with Anaconda, run the command ***conda install bokeh***

## Jupyter Notebook
Previously known as the IPython notebook, this web-application provides an interactive computational environment, in which one can combine code execution, rich text, mathematics, plots and rich media. It is a widely used platform for data cleaning and transformation, numerical simulation, statistical modeling, data visualization and machine learning. Jupyter Notebook comes preinstalled with Anaconda.

## Datasets Used
#### [Dataset1(Ebola)](https://data.humdata.org/dataset/ebola-cases-2014/resource/c59b5722-ca4b-41ca-a446-472d6d824d01)
Columns in Dataset 1: 
* Indicator  : Specifies 

                 1. how the value corresponding to it is calculated(cumulative, proportion or exact number)
                 
                 2. what is being recorded (cases/deaths)
                 
                 3. whether the cases/deaths recorded are probable/suspected/confirmed                 
* Country    : The country from where the value has been reported
* Date       : The date of reporting
* Value      : The number corresponding to the *Indicator*

#### [Dataset2(AirQualityIndia)](https://www.kaggle.com/shrutibhargava94/india-air-quality-data/data)
Columns in Dataset 2:
* stn_code : Station Code
* sampling_date: The date when the sample was taken and analyzed
* state : State/Union Territory where the sample was taken from
* location : City/Village/Town in the state
* agency : The authority that reported and analyzed the sample
* type : The type of area where the sample was taken from (industrial/residential/sensitive area etc)
* so2 : Concentration of Sulphur Dioxide in µg/m³ (microgram per cubic meter)
* no2 : Concentration of Nitrogen Dioxide in µg/m³ (microgram per cubic meter)
* rspm : Concentration of respirable suspended particulate matter in µg/m³ (microgram per cubic meter)
* spm : Concentration of suspended particulate matter in µg/m³ (microgram per cubic meter)
* location_monitoring_station : The station where the sample was monitored
* date : date of reporting

#### [Dataset3(Mushrooms)](https://www.kaggle.com/uciml/mushroom-classification/data)
Columns in Dataset 3:


![mushroom diagram](http://4.bp.blogspot.com/_d76A8FQ9xm0/SZomQ1rQyeI/AAAAAAAABFc/wQsySaXNqno/s400/mushroom+diagram.jpg)


* cap-shape: bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s
* cap-surface: fibrous=f,grooves=g,scaly=y,smooth=s
* cap-color: brown=n,buff=b,cinnamon=c,gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y
* bruises: bruises=t,no=f
* odor: almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s
* gill-attachment: attached=a,descending=d,free=f,notched=n
* gill-spacing: close=c,crowded=w,distant=d
* gill-size: broad=b,narrow=n
* gill-color: black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y
* stalk-shape: enlarging=e,tapering=t
* stalk-root: bulbous=b,club=c,cup=u,equal=e,rhizomorphs=z,rooted=r,missing=?
* stalk-surface-above-ring: fibrous=f,scaly=y,silky=k,smooth=s
* stalk-surface-below-ring: fibrous=f,scaly=y,silky=k,smooth=s
* stalk-color-above-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
* stalk-color-below-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
* veil-type: partial=p,universal=u
* veil-color: brown=n,orange=o,white=w,yellow=y
* ring-number: none=n,one=o,two=t
* ring-type: cobwebby=c,evanescent=e,flaring=f,large=l,none=n,pendant=p,sheathing=s,zone=z
* spore-print-color: black=k,brown=n,buff=b,chocolate=h,green=r,orange=o,purple=u,white=w,yellow=y
* population: abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y
* habitat: grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d