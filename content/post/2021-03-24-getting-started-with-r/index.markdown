---
title: Getting Started with R
author: Arvind Venkatadri
date: '2021-03-24'
slug: getting-started-with-r
categories: []
tags: []
output:
  xaringan::moon_reader:
    css: xaringan-themer.css
    keep_md: true
    nature:
      slideNumberFormat: "%current%"
      highlightStyle: github
      highlightLines: true
      ratio: 16:9
      countIncrementalSlides: true
---






layout: true
## Let's get started
---

### Windows

1. [Download R for Windows here](http://cran.r-project.org/bin/windows/base/release.htm)

2. Run the `.exe` file that was downloaded in the step above.

3. [Go to the RStudio Download page](http://www.rstudio.com/ide/download/desktop)

4. Under **`All Installers`** select RStudio current version ## - Windows XP/Vista/7/8/10.

5. Double click the file to install it.

6. Once R and RStudio are installed, open RStudio to make sure that you don’t get any error messages.

---


### Mac OS X

1. Go to [CRAN](https://cran.r-project.org/) and click on Download R for (Mac) OS X.

2. Select the `**.pkg`** file for the version of OS X that you have and the file will download.

3. Double click on the file that was downloaded and R will install.

4. Go to the [RStudio Download page](http://www.rstudio.com/ide/download/desktop).

5. Under `All Installers` select RStudio current version ## - Mac OS X 10.6+ (64-bit) to download it.

6. Once it’s downloaded, double click the file to install it.

7. Once R and RStudio are installed, open RStudio to make sure it works and you don’t get any error messages.


---



1.  Create a new folder on your machine with a title like:
>  **`/My_Documents/Irritating_R_Stuff/`** 

2.  Go to `Teams -> Files -> GSK Resources` and download:  
>  **`Grammar-of-Graphics-V2.0.Rmd`** ✅

3.  Save it in the folder you created above:  

>  **`/My_Documents/Irritating_R_Stuff/`** ✅

---
layout:false
# Get to Know RStudio

When you first open it, the RStudio interface is divided into four “Panes” as described below:
<center><img src="https://bookdown.org/maddocent/exploratory_data_analysis/_book/images/rstudio_interface.png" height="450px"/></center>

---
layout: true
# Get to know RStudio
<center><img src="https://bookdown.org/maddocent/exploratory_data_analysis/_book/images/rstudio_interface.png" height="350px"/></center>

---

1.Top LEFT: the **editor** where you edit scripts and documents and can “send” code to run in the console,

---

2.Top RIGHT: your **environment/history** panes. This is where you can see variables you’ve created and a full history of functions / commands you have run,

---

3.Bottom RIGHT: The bottom right pane by default contains several panes including: **files/plots/packages/help/viewer**. The files pane allows you to explore files on your computer like you would in windows explorer or finder on a mac. The plots tab is where you will see plots that you create. We will explore these various panes together in class.

---

4.Bottom LEFT: the **R console** is where the code is run. You can type code directly into the console OR you can send it to the console by running it from the editor. The placement of these panes and their content can be customized using the RStudio preferences: (From the RStudio drop down choose: **RStudio -> Preferences -> Pane Layout**). You can also drag the panes using your mouse to move / resize them.)

---
layout: true
# Where is your Work?
---

Click on: **Tools -> Global Options**:
<center><img src="https://d33wubrfki0l68.cloudfront.net/c41935ca0c88dd9ef2ee02b65222837b86d813d4/00505/2020/02/18/rstudio-1-3-preview-configuration/global-options.png" height="400px"/></center>
- Set the default working directory to **`/My_Documents/Irritating_R_Stuff/`**  

- Your downloaded file **`Grammar-of-Graphics-V2.0.Rmd`** is visible there ✅
- Click on the file
- It should open in your `Source` at top left

---

- This is an **RMarkdown** file ( file.ext = `.Rmd`)

- It will enable you to run code and write text in the same document. 

- **ALWAYS** create and save your files here!

- Do **not** work with a file sitting in your `My_Downloads` folder ✋

- More in class!!

---
layout:false
class: inverse center middle
# You R good to go!!
