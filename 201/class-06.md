***Object***


The set of variables and functions called objects, to make a model for somthimg you will know from the real world. Inside the objects we name the variabels and functions. 

The variable insdie the object called property, it is indicate about the object. Functions whihch is inside the object called method. 

For example :

var house = new Object();

house.name = 'West house';

house is **Object**
name is **Key**
West house **Value**


***Document Object Model (DOM)***

DOC control how browsers should create a model of an HTML page and how JavaScript update, access  the
contents of a web page while the browser window in it.

The DOC is a part of any browser not a html nor the JavaScript, the broswer use somthning called the DOM tree to structure this model.

**Note: Sometimes the DOM called API (Application Programming Interface).**






                             *The DOM Tree* 

<img src="https://res.cloudinary.com/practicaldev/image/fetch/s--B2Ts1hyb--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/http://i67.tinypic.com/2nqegt2.jpg">


To update the heading with the number of items in
the list, you need two pieces of information:

1. The original content of the heading so that
you can add the number of list items to it. It is
collected using the node Value property (although
i nnerHTML or text Content would do the same).

2. The number of list items, which can be found
using the l ength property on the l ist Items
variable.
With this information ready, there are two steps to
updating the content of the h2 element:

1. Creating the new heading and storing it in a
variable - the new heading will be made up of the
original heading content, followed by the number
of items in the list.

2. Updating the heading, which is done by updating
the content of the heading element using the
i nnerText property of that node