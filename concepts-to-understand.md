# Important Concepts when starting R

### Packages/Libraies

Using packages and libaries was totally foreign to me when I first started using R.  When you download R, you have what is called base R and base R has some basic functions that you can use to complete an analysis. Basic functions include sum, mean, sd, etc.

```
x <- (2)
y <- (3)
sum(x,y)
```

However many useful functions are in libraies that you will need to download. One can either download from CRAN or from Github.  To install a library from R studio,  In R studio in the bottom right quadrant you should see a screen like below. Click on install.

![](/assets/Install Library)

After you select install, you will get the following pop up dialoug

![](/assets/package install )

You will then need to type the name of the package. Typing the first letter will you provide you with auto-suggestions.

Downloading Libaries from CRAN means that the library has been tested and meet some standards--it does not guarnetee that it will work as intended. You can also download libraries

* ## Hadley or Tidy Verse

  * Embrace the tidy verse. The tidy verse is a serious of packages that will make working with R much easier than using Base R.
  * Dplyr 
* ### Working Directory

  * A concept of the working directory may be challenging for non programmers. In theory it is easy to understand--typically it is not explained in simple terms.  The working directory is a  file-folder location on your computer that you are using. If you are reading data you need to point your computer to this location. 



