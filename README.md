# day02 
1.Write a blog on Difference between HTTP1.1 vs HTTP2
A. The difference between HTTP1.1 and HTTP2 is HTTP2 is much faster and more efficient than HTTP1.1 . This is the main reason difference in it.Some of the difference are 
HTTP1.1:                                                                                
1.It works on the textual format. 
2.There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
3.It compresses data by itself.
HTTP2:
1.It works on the binary protocol.
2.It allows multiplexing so one TCP connection is required for multiple requests.
3.It uses HPACK for data compression. 

2.Write a blog about objects and its internal representation in Javascript
A.A JavaScript object is a collection of named values having state and behavior (properties and method).
Example:Car,Bike,Pen etc.

Take the example as Bike.

All bikes have the same properties, but the property values differ from bike to bike. All bikes have the same methods, but the methods are performed at different times.
Let's have an example of Yamaha YZF-R6 and list out its features:
1.Make: Yamaha
2.Model: Sports bike
3.Color: Blue
4.Fuel: Petrol
5.Weight: 190kg
6.Mileage: 20Kmpl
7.Rating: 4.5 

I will explain about objects, object properties and Methods. 

1.Objects:
Code assigns a simple value (Yamaha) to a variable named bike:
var bike = "Yamaha";
Objects are variables too. But objects can contain many values.

The following code assigns many values (Yamaha, Sports bike, Blue and so on) to a variable named bike:

var bike = {Make: "Yamaha", Model:"Sports bike", Color: "Blue", Fuel:"Petrol", Weight: "190kg", Mileage: "20Kmpl", Rating: 4.5};
The values are written as name:value pairs (name and value separated by a colon).

Syntax:
var <object-name> = {key1: value1, key2: value2,... keyN: valueN};
So,conclusion and definition for JavaScript objects is "JavaScript objects are containers for named values". 

2.Object Properties:
The name:values pairs are called properties.
Features are nothing but property and its value.
The syntax for adding a property to an object is : ObjectName.ObjectProperty = Value;
The syntax for deleting a property from an object is: delete ObjectName.ObjectProperty; 
The syntax to access a property from an object is:

objectName.property        // bike.Make   //or

objectName["property”]    // bike["Make"]   //or

objectName[expression]   // x = "Make"; bike[x]
  
So, Conclusion and definition for Java Script properties is "Properties are the values associated with a JavaScript object". 

3.Object Methods:
An object method is an object property containing a function definition.
i.e.,
Let’s assume to start the bike there will be a mechanical functionality.
function(){return ignition.on}
and so similar is to stop/brake/lights on and off etc. 

So, Conclusion and simple definition for Java Script Object methods is "Methods are actions that can be performed on objects".
