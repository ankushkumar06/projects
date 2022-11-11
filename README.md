# projects
Step 1: Create a New Project
create a new project in Android Studio. Note that select Java as the programming language.
Step 2: Before going to the coding section first you have to do some pre-task
Add Images: All the images are listed below. Save them in your drawable folder in resources. Go to the app > res > drawable and paste the following files:
Grid
O
X
Change the style to NoActionBar in themes.xml file: 
<style name=”AppTheme” parent=”Theme.AppCompat.NoActionBar”>
Step 3: Working with the activity_main.xml file
The XML codes are used to build the structure of the activity as well as its styling part. It contains a TextView at the very top of the activity to display the title. Then it contains an ImageView of the grid and in each box, there is an ImageView. At the bottom of the activity, there is a TextView to display the status of the game. Below is the code for the activity_main.xml file.
  Step 4: Working with the MainActivity.java file
We will create a two-dimensional array that will store all the winning positions. We will create a function that will run when a box inside the grid is clicked. Inside this function, we will first check if the box selected is empty or not. After that, we will set the image of X if the last move was of O or we will set the image of O if the last move was of X. Then we will check if the move has reached the move position and then reset the game. Below is the code for the MainActivity.java file. Comments are added inside the code to understand the code in more detail.
  
