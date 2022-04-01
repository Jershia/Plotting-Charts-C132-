# Plotting Charts
* *We plotted different charts in this class.*
* *We learned about different types of planets.*
* *We applied K-Means Clustering Algorithm on the Data to find insights.*

## Steps To Scrape data
  * *We had a variable low_gravity_planets containing the list of all the planets with gravity less than 100m/s.We observe the headers and see that there is a header known as planet_type.*
  * *Here, we use the set() function to remove all the duplicates and keep the unique values only*
  * *We get 4 different types of planets such as:*
     * *Neptune-like - These planets are like Neptune! They are big in size and they are made of ice.*
     * *Super Earth - These are the planets that have mass greater than Earth but smaller than that of Neptune (Neptune is 17 times of Earth).*
     * *Terrestrial - It is a planet that is composed primarily of silicate rocks and metals (Earth, Mars).*
     * *Gas Giant - These are the planets that are mainly composed of Gases (Helium and Hydrogen) like Jupiter and Saturn.*
  * *Let’s plot a scatter plot where we have X-Coordinate as the radius of the Planet and Y-Coordinate as the mass of the planet.*
  * *Here, using the Elbow method (remember when we learnt about K-Means and (Clustering) we can see a descent up to 4, after which it is not significant.*
  * *When we found the number of unique planet types earlier, there were 4 types but when we looked at the scatter plot, we couldn’t detect the number of clear clusters.Machine learning can do things that we ourselves couldn’t do!*
  * *Plot the previous chart with color coding based on the planet’s type.*
  * *Given what we have learnt about different types of planets, we can say that life can be possible only on terrestrial planets and super earth like planets. At least, for us.Let’s take the list of planets with low gravity and filter out more planets based on their type and create a new list.*
  * *We are now left with 1,452 planets that can host us.*
 
## Code is given below
https://colab.research.google.com/drive/1vDMR04DbOORhWjRJvd2qFIwzuzW_4Fqb#scrollTo=VRAYWyerVKXP
