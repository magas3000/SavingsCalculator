# SavingsCalculator
An Android App that allows you to create, save and edit multiple savings plans.

- # Description
  - In each individual plan you can calculate the total amount of money in your savings account with the added compounding interest after a certain number of years.  
  - You can enter your desired interest compounding period, including continuous compounding(enter 0 in the compounding period field to perform continuous coumpounding).  
  - You can adjust the outcome for inflation, if desired, by providing the current inflation rate.  
  - You can also export the savings plans and their contents into a CSV file that will be located in the Documents folder of your device.

A gif displays the first time you boot the app, greeting you:  
![Splash Screen](/gifs/Splash-Screen-Showcase.gif)

The main activity is a Recycler View that contains the swipe items, an add button to add plans to the Recycler View and an export button to save all your plans in your Documents folder:  
![Main Activity](/gifs/Main-Activity.gif)  
  
Selecting "Add" displays the following dialog:  
![Main Activity Add](/gifs/Main-Activity-Add.gif)  
  
Selecting "Export" requests permission if it is the first time doing it. When exporting is done a message will display at the bottom of the screen:  
![Main Activity Export](/gifs/Main-Activity-Export.gif)  
  
You can swipe to reveal edit and delete:  
![Main Activity Delete Action](/gifs/Main-Activity-Delete.gif)  
  
Selecting edit allows you to access the plan's calculator activity:  
![Main Activity Edit Action](/gifs/Main-Activity-Edit.gif)  

Once in the Calculator Activity, you can fill in the required fields and calculate your future savings account balance:  
![Calculator Activity](/gifs/Calculator-Activity.gif)  

## __Open-Source 3rd Party Libraries Used:__

* **Glide** - An image loading and caching library for Android focused on smooth scrolling.  
* **OpenCSV** - An easy-to-use CSV parser library for Java.  
* **SwipeRevealLayout** - Easy, flexible and powerful Swipe Layout for Android.  

## __Application Icon Used:__
> <div>Icons made by <a href="https://smashicons.com/" title="Smashicons">Smashicons</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>