backbrush
=========

BackBrush is a markup language based, AI driven art modeler. It is a cyber-artist which targets to replace drawing techniques with markup language. It’s mainly a web service where the user describes the scene, model and texture the scene through code. BackBrush takes all the descriptive parameters and start drawing in its own will. 

Features
=========
Main Features of BackBrush is like a human artist. Its drawing will never be the same. It works like any graphics programming language, where user defines the shape and structure of any model. But in BackBrush the user does not need extensive knowledge about computer programming nor mathematical experience. He will describe the scene with available BackBrush attributes with markup language and it will take care of the rest.
BackBrush is not Photoshop, human artist, 3d modeler, animation tool, cartoonify and any other image manipulating software. It will make art on its own. But the description must be provided by the user. Then BackBrush outputs image based on machine learning and artificial constrains.
So the big feature of BackBrush is creativity will be on the user’s side, performance will depend on how well the user described the scene, model or texture. BackBrush does not want to replace the user totally. It wants to fill the gap between a person who have good imagination for art but does not have the skill to do so.
Another feature of BackBrush is after every drawing it will be wiser. It will learn something new every time no matter what user will use it. That’s why we are trying to make it web based service.


Modules
=========
-	Parser: This web based parser will parse the markup language given by the user, possibly XML. It will gather and categorize the attributes user given for the art. Any error will be given if not enough or unrecognized attribute given.

-	Neural Network Kernel: This is the core of the BackBrush. After parser feeds the attributes this core will determine where to start drawing, which to draw and how to draw. It will determine the colors and shapes of the models.

-	A Webgl based , artificial constrained drawing tool: After having direction of which to draw and how to draw, it will get the shape from the kernel and start drawing. We will set artificial constrains, like hand movement limitations to it. We think without restricting or rather forcing it train the program to draw like a human artist, it will never draw like a human artist. If it has a constrain, it will find a different way. For example, it is not possible for a human artist to draw a circle at one stroke perfectly. So an artist makes little corrections along the way and make small progress at a time by wrist movements. BackBrush will learn to draw like that way, and after learning it will serve the shapes like human do art.
-	
Alternatively, if this system does not work, this drawing tool will converts the shapes into triangles, which is called triangulation. Then it will start to create the shapes by fitting this triangles. Part of it will be done by webgl.
