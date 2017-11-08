# Setting up R and RStudio in Windows

## Installing R
* Open your browser and go to http://cran.r-project.org/  
* Click on `Download R for Windows`  

<img src="Figures/download_R01.PNG" alt="" width="300"/>

* Click on `base`  

<img src="Figures/download_R02.PNG" alt="" width="300"/>

* Click on `Download R 3.1.2 for Windows`   

<img src="Figures/download_R03.PNG" alt="" width="300"/>

* Open and run the file you just downloaded `R-3.4.2-win.exe` 

<img src="Figures/download_R04.PNG" width="100"/>

* There is no need to change the default installation!  

|  |  |  |
|:-------------:|:-------------:|:-------------:|
| <img src="Figures/install_R00.PNG" alt="" width="175" /> | <img src="Figures/install_R01.PNG" alt="" width="175"/>| <img src="Figures/install_R02.PNG" alt="" width="250"/> |
| **1** | **2** | **3** |
| <img src="Figures/install_R03.PNG" alt="" width="250" /> | <img src="Figures/install_R04.PNG" alt="" width="250" style="PADDING-LEFT: 5px; PADDING-RIGHT: 5px;"/>| <img src="Figures/install_R05.PNG" alt="" width="250"/> |
| **4** | **5** | **6** |
| <img src="Figures/install_R06.PNG" alt="" width="250"/> | <img src="Figures/install_R07.PNG" alt="" width="250" style="PADDING-LEFT: 5px; PADDING-RIGHT: 5px;"/>| <img src="Figures/install_R08.PNG" alt="" width="250"/> |
| **7** | **8** | **9** |
| <img src="Figures/install_R09.PNG" alt="" width="250"/> | <img src="Figures/install_R10.PNG" alt="" width="250" style="PADDING-LEFT: 5px; PADDING-RIGHT: 5px;"/>| **DONE** |
| **10** | **11** | **12** |


## Installing RStudio  

* If you have already installed RStudio, before you skip this section check if you are using the right R version. Go to `Tools/Global Options`. Make you sure you have `R-3.4.2` under R version.  

<img src="Figures/RStudio_Rversion.PNG" alt="" width="300"/> 

* Go to http://www.rstudio.com/ and under `RStudio` click on `Download` .  

<img src="Figures/download_RStudio01.PNG" alt="" width="300"/>

* Under `RStudio Desktop`, select `DOWNLOAD`  

<img src="Figures/download_RStudio02.PNG" alt="" width="250"/>

* Download the installer for Windows.  

<img src="Figures/download_RStudio03.PNG" alt="" width="250"/>

* Open and run the file you just downloaded `RStudio-1.1.383.exe` 

<img src="Figures/download_RStudio04.PNG" alt="" width="100"/>

* You don't have to change any of the defaults for the installation  

|  |  |  |
|:-------------:|:-------------:|:-------------:|
|<img src="Figures/install_RStudio00.png" alt="" width="200"/> | <img src="Figures/install_RStudio01.PNG" alt="" width="250" style="PADDING-LEFT: 5px; PADDING-RIGHT: 5px;"/>|<img src="Figures/install_RStudio02.PNG" alt="" width="250"/>|
|**1**|**2**|**3**|
|<img src="Figures/install_RStudio03.PNG" alt="" width="250"/> | <img src="Figures/install_RStudio04.PNG" alt="" width="250" style="PADDING-LEFT: 5px; PADDING-RIGHT: 5px;"/>| <img src="Figures/install_RStudio05.PNG" alt="" width="250"/> |
|**4**|**5**|**6**|


## Installing devtools
* Open Rstudio, in the **Files/Plots/Packages/Help** panel, select **Packages** and then click on **Install** 

<img src="Figures/devtools00.png" alt="" width="400"/>

* Type `devtools` under **Packages**, make sure you spell the name of the package correctly. Then, click on **Install** 

<img src="Figures/devtools01.png" alt="" width="400"/>  

* Alternatively, you can run the following command in the console.  

```
install.packages("devtools")
```
## Installing packages from GitHub
* We are ready to install R packages from GitHub 
* First we need to load the `devtools` package

```
library(devtools)
```

* Now we can install the `gapminder` package.  

```
install_github("jennybc/gapminder")
```

**License**  

 http://opensource.org/licenses/MIT
