AandroidApivizSetup
===================

Simple Apiviz Setup for Android Developers using the Eclipse IDE. Note, to put 
multiple paths per javadoc commandline you use the semi-colon between the paths(you will use it 
to inlcude multiple android framework jars and your library jars for the project ).

The other note is that for things like header, bottom,etc you can use the @argfilename
to point to an argfile that has the stuff for that entity, easier to use when you have
long things like the doctitile, etc.

Read the jvadoc.xml ant file.

Basic premise is that Google seems always to goof up the android sdk ant files so 
run all stuff via IDE thus do not have to wait to update any ant scripts, AGILE AT FULL SPEED.


The first pass looks like this:

![First Pass](https://github.com/shareme/AndroidApivizSetup/raw/master/readme.assets/firstpass.png)



To Use
=======

Edit the javadoc.xml file to replace my paths with yours. Than right click file in your IDE and run as ant file.



Resources
=========

[Apiviz Eclipse details](http://code.google.com/p/apiviz/)

[Javadoc Tool commandline options](http://docs.oracle.com/javase/1.4.2/docs/tooldocs/windows/javadoc.html#javadocoptions)

[My blog](http://fredgrott.wordpress.com)


License
=======

Apache License 2.0