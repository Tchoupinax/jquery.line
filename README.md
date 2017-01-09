jquery.line
===========

## Customization 
#### 09.01.2017
Add the customization of the line's class directly from builder options.
Now, the div which represent the line can be obtained by the return of line.

## ****************************************************************************

###Draw a line between two points in the given container.

Usage:

var myDiv = $(selector).line(x1,y1,x2,y2,options,callback);

$('#example').line(0, 0, 20, 20);

You can pass some options like color, stroke width or zindex, and a callback function:

Defaults are:
  { zindex : -1,
    color : '#000000',
    stroke: '1',
    style: 'solid',
    class: 'drawingLine'
  }

Example: 

$('#example').line(10, 10, 300, 300, {color:"#D60004", stroke:5, zindex:1001}, function(){alert('Hello new line!')});

Open index.html in the 'example' folder on your browser to see some lines.


