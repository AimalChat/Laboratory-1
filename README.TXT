Project "figures"
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 1.

This is a very simple project to demonstrate some characteristics of
objects.

You can create various shapes, and you will see, if you do, that those
shapes are drawn on screen (in a window that we call the "canvas").

You can then manipulate these objects: change their position, size and 
colour. Try it out: create a few different squares, triangles and circles.

This project is designed as a first example of object-oriented programming.
It illustrates a number of concepts:

 - a Java project (application) is a collection of classes
 - objects can be created from classes
 - from any one class, many objects may be created
 - objects have operations (methods)
 - operations can have parameters
 - parameters have types (at least String and int)
 - objects hold data (fields)
 - the operations and fields are common to all objects
 - the values stored in the fields can be different for each object

The project also demonstrates

 - BlueJ object creation
 - interactive method invocation
 - parameter passing

A good second project to look at after this is "picture", which adds a class
to those ones in this project. That class (named "Picture") uses the shapes
to draw a picture. It can be used to experiment with coding.

Aimal's Note : Im currently learning the very basics, shapes and classes! 
Im still terrified of what's to come during this semester but I feel thrilled
having the opportunity to begin this new journey!

Lab report (part a = question, part b = answer to said question)

1a.Which files from BlueJ’s local project are uploaded to the repository, and 
which are not? Why do you think this is? 

1b.The files uploaded on the repository include : Canvas.java, Circle.java, 
Person.java, README.TXT, Square.java, Triangle.java, package.java. 
I believe that these files in particular stayed due to the .java extension 
they have, making them the only ones that can be modified in the IDE.
Since BlueJ's language is Java, it would make sense that the only files 
that are inserted in the IDE are the ones with the .java extension.
The other files weren't inserted due to their different nature (.class and .ctxt)
However, I think that the one exeption, the README.TXT file, 
is in the IDE because it is a file that is supported by the system and thus generated 
by said system. Also, every program comes along with a README.TXT file if so desired.

Lab : Figures project (chapter 1) (part a = question, part b = answer to said question)

1a. What happens if you call moveDown twice? Or three times? What happens if you call 
makeInvisible twice?

1b. Seemingly nothing happens when you moveDown twice and when you makeinvisible twice.
(I think it’s because the circle and square are already invisible, thus any movement
or an already attained property will not change anything whatsoever.) 

2a. Try invoking the moveVertical, slowMoveVertical, and changeSize methods before 
you read on. Find out how you can use moveHorizontal to move the circle 70 pixels 
to the left.

2b. Firstly, you right click on the Object : circle1 and selecting the void 
moveHorizontal(int distance) By now, a small screen will pop up titled method
call. After typing in the desired variable in the box where int distance 
remains as a placeholder (i.e : Circle1.moveHorizontal(70)), you confirm
the command and the circle will do as told, moving 70 pixels to the right?
Oh. Since it moves on the x axis, you need to treat it as you would on a Cartesian
plane. So, 70 will move it to the right whilst –70 will move it to the left.

3a. Invoke the changeColor method on one of your circle objects and enter the 
string “red”. This should change the color of the circle. Try other colors.

3b. To change the color of our circle, you need to not only write red, but “red”
with the quotation marks! Be careful or else nothing will change since the 
variable red does not exist to the computer (Program).

4a. This is a very simple example, and not many colors are supported. See what 
happens when you specify a color that is not known.

4b. When I put in the command: “pink” and “brown” into the method calling pop up
,the circle became black as if it were the default.

5a. Invoke the changeColor method and write the color into the parameter field 
without the quotes. What happens? 

5b. I found that, without the quotation marks, the command will not be recognized
and specify that the symbol inputted in the parameter field (ITC, variable red) 
cannot be found.

6a. Make sure you have several objects on the object bench, and then inspect each 
of them in turn. Try changing the state of an object (for example, by calling the
moveLeft method) while the object inspector is open. You should see the values in 
the object inspector change.

6b. Something I noticed : When using the slowmovehorizontal or vertical, the private
int xPosition remains static even if we see the transition bewteen positions. It only
counts the amount of pixels moved after the fact.

7a.Figure 1.8 shows two different images. Choose one of these images and recreate it 
using the shapes from the figures project. While you are doing this, write down 
what you have to do to achieve this. Could it be done in different ways?

7b. (I chose the house.) When first starting out, I observed the photo and started
placing in all the shapes I would need to make the image a reality. (ITC, it was 2
squares,1 circle and 1 triangle.) After dropping the necessary shapes in my canvas,
I began to change the colours of each shape. I then started guestimating what
dimensions the shapes had on the picture. After much trial and error and moving each
shape in small increments, I was finally able to finish replacating the image, somewhat.


      