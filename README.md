
# Foundamentals and Practice of Software Engineering


[![DOI](https://zenodo.org/badge/43438544.svg)](https://zenodo.org/badge/latestdoi/43438544)

* [The non-interactive preview on nbviewer](http://nbviewer.ipython.org/github/PySEE/home/tree/S2020/notebook/) 

* The interactive notebook on Binder [![the interactive notebook on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PySEE/home/S2020)

This course is intended to train **students in thermal energy power engineering** become skillful at making productive use of computational techniques. 

We will cover: 

* write clean, testable, high quality code in [Python](https://www.python.org/)
* using [Numpy, Scipy, Matplotlib](https://www.scipy.org/) to model and understand data
* apply [Computational thinking](https://baike.baidu.com/item/计算思维) to model and solve the complex problems
* write [unit tests](https://baike.baidu.com/item/单元测试) and [profile](https://baike.baidu.com/item/性能分析) the software performance
* using [GCC and Make](https://gcc.gnu.org/) to build C/C++ and [Fortran](https://baike.baidu.com/item/FORTRAN语言) applications
* version control with [Git/Github](https://git-scm.com/) 
* C/C++ and Python programming in [Linux/Ubuntu](https://www.ubuntu.com/)

We emphasize breadth rather than depth on the these topics. The goal is to provide you with a brief introduction to more essential topics of computer knowledge and keep pace with the latest developments in computer technology in the short course. 

If you have concerns about the course, please email(cmh@seu.edu.cn) to me or open [the github issue](https://github.com/PySEE/home/issues). I value all suggestions.

**行是知之始，知是行之成 - 陶行知**

[Practices](https://github.com/PySEE/Practices/) are the very important part of the course. You will have to spend a lot of time and effort to do challenging enough practices.

We highly recommend you practice coding whenever you have a few minutes.

After successfully completing the course, We wish you have a broad spectrum of of computer knowledge and is a good programmer in the context of using computation to solve complex problems.

## Required Materials

* A laptop **computer** will be needed in the classroom.

* **Softwares** : Python, GCC, Git, VS Code and WSL/Ubuntu etc.
   
* **Reference Textbooks**

   * John V. Guttag. [Introduction to Computation and Programming Using Python : With Application to Understanding Data(Second Edition)](https://mitpress.mit.edu/books/introduction-computation-and-programming-using-python-second-edition). MIT Press, 2016.
  
   * Peter Prinz,Tony Crawford: [C in a Nutshell(2nd Edition)](https://github.com/oreillymedia/c-in-a-nutshell-2E). O’Reilly Media, Inc. 2016

   * Michael J. Moran. [Fundamentals of Engineering Thermodynamics(7th Edition)](https://github.com/FOSSEE/Python-Textbook-Companions/tree/master/Fundamental_of_Thermodynamics_by_Moran_and_Shapiro). John Wiley & Sons, Inc. 2011

## Schedule and Structure

* The course schedule and structure are listed in the [**Outline**](./Outline.md)

## Contents

* **PySEE/HOME**
   
   * [Jupyter Notebook for the course](./notebook) 

      * [The non-interactive preview on nbviewer](http://nbviewer.ipython.org/github/PySEE/home/tree/S2020/notebook/) 

      * The interactive notebook on Binder [![the interactive notebook on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PySEE/home/S2020)
    
   * [Guide](./guide)  

      * [Building Software Environment](./guide/doc/BuildingSoftwareEnvironment.md) Python,Jupyter,SciPy,GCC,etc.
      
      * [References](./guide/doc/References.md)

* [PySEE/SEUIF97](https://github.com/PySEE/SEUIF97) IAPWS-IF97 high-speed shared library (Windows32/64, Linux64); API: Python,C/C++,Excel VBA,MATLAB,Java,Fortran,C#

* [PySEE/PyRankine](https://github.com/PySEE/PyRankine) The rankine cycle simulator to demonstrate the general abstraction 

* [PySEE/Practices](https://github.com/PySEE/Practices) The information of practices: tasks, grading standards and submission

## Grading

The Course graded on an 100 point scale and then weighted according to the following distribution:

  * In-class Exercises: 20
  * [Practices:50](https://github.com/PySEE/Practices/)
  * Final Exam: 30

## Using the Notebooks of PySEE/home 

`download/clone` the repository to your computer,then start Jupyter to  **interactive** with the notebooks.

* Download the *PySEE/home* Repository  

  You can manually download the `zip` file of the `PySEE/home` to your computer

  ![download](./guide/doc/img/downloadhome.jpg)

* Using the Jupyter Notebooks of PySEE/home:  

   Unzip the **zip** file, then, in the sub-folder of **notebook** of home, double-click `nb.bat`(OS:Windows) or run the command:`jupyter notebook` in a terminal. This will open a web page in your browser with a list of the available notebooks.

>We **recommend** that you use [git](https://git-scm.com/) to clone and update the home repository
>
>**Cloning the S2020 branch of repository shallowly for saving bandwidth**
>
>```bash
>git clone --depth 1 -b S2020 https://github.com/PySEE/home.git
>```
>**Updating to The Latest Version**
>
>```bash
>git pull
>```

## Cite as

Cheng Maohua. (2020, March 13). PySEE/home: First Release of Courseware (Version V1.0.0). Zenodo. http://doi.org/10.5281/zenodo.3709440
