# Different Shapes and Design Test using SVG in the Web browser

Frontend coders who code every day they know what is HTML and CSS they design their web template using these two technologies. Sometimes they use javascript for making their work more attractive to their client. However, HTML SVG has more facilities to make this web design interesting to the users.

Therefore, SVG stands for Scalable Vector Graphics and it is a language for describing 2D-graphics and graphical applications.

Moreover, SVG is mostly useful for vector type diagrams like pie charts, two-dimensional graphs in an X, Y coordinate system, etc.

Now we shall begin our work with this SVG using simple HTML and CSS.

At first, we should define our html5 structure. Then, we will implement our circle using this SVG. Below screen shot will help to make that structure. 

![alt text](https://github.com/Maxyee/Glostars_Web_Template/blob/master/HtmlSVG/readmeShots/circlecode.png)

After making this Html file. we have to give CSS design into that html structure. so below code should be added
in a different file called Style.css

```
#svgitemcircle{
    position: relative;
    left: 50%;
    -webkit-transform: translateX(-20%);
    -ms-transform: translateX(-20%);
    transform: translateX(-20%);
}

#svgeitemrectangle{
    position: relative;
    left: 50%;
    -webkit-transform: translateX(-50%);
    -ms-transform: translateX(-50%);
    transform: translateX(-50%);
}
```
the output of this code will look like below screenshot

![alt text](https://github.com/Maxyee/Glostars_Web_Template/blob/master/HtmlSVG/readmeShots/circle.png)

into this code we saw that there was 'cx', 'cy', and 'r' value for making that circle where
'r' means the radius of that circle the bigger of that 'r' will make bigger circle
'cx' means that how much space it will take in x-axis
'cy' means that how much space it will take in y-axis
furthermore,we can also define the color of that circle using the 'fill' attribute which was red

By following the same process, we can make a rectangle using this SVG feature. Below screenshot will help to make this rectangle

![alt text](https://github.com/Maxyee/Glostars_Web_Template/blob/master/HtmlSVG/readmeShots/rectangle.png)

Also we should use the same CSS code for this rectangle too.

the output of this code will look like below screenshot

![alt text](https://github.com/Maxyee/Glostars_Web_Template/blob/master/HtmlSVG/readmeShots/rectangleScreenShot.png)


