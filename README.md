#Colorful Exceptions

This method will take in a string for a url, have the driver go to it. Then display an alert once it has determined the css background color of the element. The alert will only pop up if there is a css style with background set to a specific color. If there is no background color attached to the element located at the specified xpath, the application will throw an InvalidColoredElementException. It will also have a couple list of arrays, if the color does not fit as one of the colors, throw the appropriate exception:

warmColors [red, yellow, orange] InvalidTempertureException > InvalidWarmthException

coldColors [blue, purple, green] InvalidTempertureException > InvalidColorException

badColors[ #E80C7A, rgb(232, 44, 12), black ] UnlikedColorException > JFUnlikedColorException

Create a test case which uses the method you created for each type of exception. 


[Christian Mallapre] (http://www.mallaprechristian@yahoo.com/) 
