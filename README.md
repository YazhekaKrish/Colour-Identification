<h1>COLOUR IDENTIFICATION</h1>
<h3>
This module helps us to identify various range of colours in a picture.
</h3>
</h2><b> ABOUT PROJECT</b> </h2>

In this project, we are going to build an application through which you can automatically get the name of the color by clicking on them. So for this, we will have a data file that contains the color name and its values. As we move the cursor to various positions in the picture we will be able to know the different colours present at that exact position.Colour detection is necessary to recognize objects, it is also used as a tool in various image editing and digital art apps.

</h2><b> DATASET </b> </h2>

Range of colours are made up of 3 primary colours red, green, and blue. In computers, we define each colour value within a range of 0 to 255.That is 256*256*256 = 16,581,375. There are approximately 16.5 million different ways to represent a color. In our dataset, we need to map each color’s values with their corresponding names.

The CSV file for our dataset are found in this link:
<a href="https://github.com/YazhekaKrish/Colour-Identification/blob/main/python-project-color-detection/colors.csv">DATASET</a>

The colors.csv file includes 865 color names along with their RGB and hex values.

</h2><b> REQUIRED LIBRARIES </b> </h2>

The computer vision library of Python that is OpenCV and Pandas must be downloaded.
OpenCV, Pandas, and numpy are the Python packages that are necessary for this project. 

To install them, simply run this pip command in your terminal:
```ruby
pip install opencv-python 
```
After downloading opencv succesfully, run the next command.
```ruby
pip install pandas
```
</h2><b> STEPS TO BE FOLLOWED </b> </h2>

Download the folder from the link:
<a href="https://github.com/YazhekaKrish/Colour-Identification/blob/main/python-project-color-detection">DOWNLOAD FOLDER</a>

Open the code in python IDLE and run the code in your compiler.
```ruby
cd <Enter the path of the dowloaded folder>
```
```ruby
python color_detection.py -i <add your image path here>
```
</h2><b> OUTPUT </b> </h2>

Place the cursor at different spots and the respective name of the colour pops on top of the picture.
