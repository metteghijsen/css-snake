# CSS-snake

## Project description
This is a project I made in my second year as a result of one of my teachers' CSS masterclass. There is no Javascript in this project. Therefore it is not very complicated.

## Installation
You can "install" this web page by downloading it and running it on a live server. You could use an external application such as XAMPP for this purpose. IDEs like Visual Studio Code have this feature built in.

When using XAMPP it is important to put the project in the htdocs folder. Then you can click on the Apache module. When you go to your browser and type in localhost/project name, it should open.

In case you have Visual Studio Code installed, you can open the project in there. Clicking on the 'Go Live' button in the status bar will open a live server where you should be able to see the project.

## Usage
If you go to my [school-website](https://i481695.hera.fhict.nl/css-snake/), you can use the project without installing it.

When you hover over the dark square in the center of your screen, small squares will appear and disappear over time. If you do this quickly, a creeper from Minecraft will appear.

## Architecture
Because there is no Javascript in this project, the architecture of the site is not very complicated. In the HTML file, there is a large grid formed of 64 divs. These form a square of 8x8. I have calculated with X and Y coordinates where the eyes and mouth of the creeper should be. These places are black by default. The rest of the colors (different shades of green) are determined in a pattern in the CSS file. 
