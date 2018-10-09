
## Contents
- [What OpenITS  is](#what-OpenITS-is)
- [How OpenITS  works](#how-OpenITS-works)
- [How to use OpenITS ](#how-to-use-OpenITS )
- [Future Plans](#future-plans)
- [Support me](#support-me)

## What OpenITS  is
OpenITS  is a python script that takes in as input an image, and returns a text output that resembles the input image.
In other words, it replicates an image with certain characters.

For example, when the following image of Octocat - 
![](https://github.com/cumtlzc/asciify/blob/master/1.jpg)

is passed as a parameter into OpenITS , the following output is observed -

```
***********************S***************************?%S?***********************************
************************?SS*********#%#************S%%%***********************************
************************SSS*?******#@@@@@@@S****??S%%%%***********************************
***********************?SSS%S****S@@SSS%S%@@?***S%***%#?**********************************
***********************?S****?%S@@@S@@S@S%@@?#SS*******S**********************************
************************S*******@@@@S@@##%#@************#?********************************
************************S****SS@@@@??%@#@##S#%%?*********?********************************
************************?**SS%*@@S??%S@@#S@@@#**#%%S%****?********************************
****************************%%?@@?%???S@###@@SS*#?*#?*****S*******************************
***********************S***S%%%@@%%%?%@@@#@@@?%%?%?%%******#******************************
********************%??S**?*S%%@@@%S?%@@@@@@S@???%??%%*****?#*****************************
******************?%????#@%SSSS#@@@SS#@@@SS%#???????%%%?*****?****************************
******************%?????%SS%%%%@@@@SS@@@@@@?%?????????%%?****#***********?*??%?????????*?*
******************%?????%%%?S%%@@@SSS@@@@@%?????????%%%%%%***%*********%S%?????????????***
*****************%??????%%S%?SS@@##SS@@@@??????%?????%%%%%***%S*****?%SS%%?????????????***
*****************S%??%%%%S?%*%@#S%?S##@@??%%%%%?%%%%%%%%%%%**#S??***S#SSS%????????????****
*****************%%%?%%SSSS##S??%?%?%#@@%??%%??%??*S%%S?*%??#S##%**?SS##SS%%??????????****
******************S%%%S#%%@#????%%???S##@SSS@%%?%?***?SS*****?##***S##S######?????????****
*****************S*?###@@@@#%%%%S%%?S##@@@S@@@S%??S??*#S??**??##%**#####S#%?????????******
****************#S%*##@@@@@##SSSSSSS@%S@#@@@@@@S%%%@??#?#?????S##?*?####?SSSS???????******
***************S#S?*##@@@#S*#@@@?#@###@#@@@@@@@@###S#@##?%%???%%#?**#@S##SS?%?????*?******
**************?SS%**##@SSSS??#S#%%%%%S#@@@@@@@@%S*@@@@#@#%?????%%??#%##S%#%S%%???*********
***************SS*******SS%?*?%%%%??%%@@@@@@@#@??#?%@@@@%?????%%S#%?**%####SS%?%**********
**************S#?********SS***S%?%%?%%S#@#@@@@*%***%###%%%??#%##S#?%**??##?SS?************
*************%SS********?S%****%%%%?%%%@%SS?@#@****%###%%%?##S%S?#?***********************
************%SS**********S?****#%%%%%%S%%%S#@%******#SS*?%#SS%%?#?************************
************SS***********S%***?%%%S%?%S%###SSSS?****S#S?***?#?SS#*************************
***********?S************?S****#%%%%%%%%#S#%#S%%%****#SS***?S#S##*************************
***********SS*************S**S@#S#SS%%%#@S%%#%%SS?***#S%***?S?@SS*************************
***********SS*************%**S@S###%%S#@#S%%%%%%SS***%#?**S*?S%#%*************************
***********?S*****************#%S##SSS@@#S%%??%%SS?**S#****#*#S#**************************
************S****************SSSS@##@##@S%%%?%%#SS#**SS****?@%S***************************
******************************?S#@#@@#S#S%%??%%S####*#******?S##**************************
***************************%S%%SS@#S####S%%?%%SSS#@##%******S*%?*#************************
***********************S###%%%SSS##@#%%SS%%%%S#S####S%*****?***#?**#**********************
*********************SS%%%S%SS#?@#@#SSSSS%%@SS@S##@@##*****?****%#**?*********************
*******************%S%%S%S#*S?@#####%%SSS@@#?#@@####@#S?**********#?%*********************
******************%S%%SS*?**?#####S%??SSS@%S%S##########S***SSSSSSS##*********************
******************##SSS****@#####%S%%%SS##S%@@###@SS#####SSSSSSSSSSSS#%%%%****************
******************##*****?###?**%%??S#S#@@SS#@#S####@@#@#####SSSSSSSSS##SS%%%%************
******************%*****?##@***%SS?%SS@###SS####S###@##@#####SSSSSSSSSSSSSSS%%%%**********
***********************?@@@***S%??S#S#@##SSS@S######@@@@##@#SSSSSSSSSSSS#SSSS%%%%%********
***********************@@@@***S??S#@S@##SSSS********?#@#@###SSSSSSSSSSSSS#SSSS%%%%%%******
***********************@@@****SSS#%?#@@@SSSS********S@*#@#####SSSSSSSSSSSSSSSSSS%%%%%*****
**********************?@@#***?###**#@@@###S#************#######SSSSSSSSSS%S??%%%%%%%%%****
***********************@@?****@@?**@@@@##S@@S*************??#SS#SSSS#?**********???%%%%***
***********************@@*****%@***@@@@@@@@@@************S*#**************************%%?*
***********************@@******?***@@@@@@@@@@#***********#**S***************************%?
***********************@@**********@@@@@S@@@@@#**********#**??***************************?
*********************?#@@?*********@@@@@*#@@@@@S*********@***#****************************
********************%##@#*********?@@@@%**#@@@@@********?****??***************************
*******************S#@S@@?********@@@@@?***@@@@@%*******@?****?***************************
*****************%######S********?@@@@@?***#@@@@S*******?*****%***************************
****************?%#@#%S#S?*******@@@@@@?****@@@@@******S?*****#***************************
*****************S*###S%#********@@@@@@*****#@@@@******@%****?#***************************
******************%*%*??*%******#@@@@@@*****?@@@@******@#?***@@***************************
******************#*S**#********@@@@@@*******@@@@******@@#***@@***************************
********************#***********@@@@@%*******#@@@********?***@@#**************************
********************?**********?@@@@@*********@@@?************@@**************************
***************************?***@@@@@**********@@@??***************************************
**************************??%?#@@@@S**********S@##S?**************************************
***************************?S%S@@@#*?*******?##@###S**************************************
**************************%SSSS%%SSS?********#######?*************************************
**************************?SSSSSSSSS??********####@***************************************
**************************%SS#SSS%SS?**********S@@@S**************************************
***************************?@@###S?*************@##@@*************************************
**************************?@@##@@**?***********#@###@*************************************
***************************?@S#@#?*************#@#@@@*************************************
***************************#@#@%****************#@@*@*************************************
**************************?###@?***************S#@S*@*************************************
**************************#%#%#**************?###@**@*************************************
**************************#@@S#***********************************************************
*************************##@#S#?**********************************************************
*************************S#SSS#***********************************************************
************************#S#SSS#***********************************************************
```
-------------------------------------------------------------------------------------------------------
## How OpenITS  works
ASCIIFY works in a rather simple and intuitive way.
Here's the algorithm -
- Resize the image to a standard dimension, while maintaining aspect ratio
- Convert to grayscale (the reason for doing so is because characters are replaced based on their intensity)
- Create list of special characters to replace pixels with
- Classify and divide pixels into buckets or groups, based on their intensity
- Replace all pixels in a bucket with the corresponding special character
- Print the text into terminal or write into a file
- Profit!

-------------------------------------------------------------------------------------------------------
## How to use OpenITS 
- Ensure you have the required dependency "PIL" for Python installed. (pip install pillow)
- Clone the repo
- Run the python script, and pass the image path as the parameter
- The script will print the output in the terminal, and will also write into a file 'img.txt' in the same directory as the python script
- Profit!

-------------------------------------------------------------------------------------------------------
## Future Plans
- Alternatively support colored outputs by printing the text onto an image

-------------------------------------------------------------------------------------------------------
## Support Me
If you liked this, leave a star! :star:

If you liked this and also liked my other work, be sure to follow me for more! :slightly_smiling_face:
