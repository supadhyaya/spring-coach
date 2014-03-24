Author : Upadhyaya Sanjiv.

Background :
----------

After working in data science for couple of years I have decided to soak my feet in web development.There are lots of frameworks and programming language which we can choose to do this thing. Personally I believe that only after running through the steep curve of Spring (obviously with JAVA as programming language) one can truly master the basics as well as core of web app development. They you can gladly take your career path to other frameworks and programming language as well. 

I don't have a very good knowledge in web application development and spring is something which I know I will struggle a lot with. I am already struggling but I am adamant about fucking this shit for once and for all. Please pardon my language as this is what I really feel about deep diving into web application with Spring. 

Wait !! Wait !! don't go away. Its actually good for you that you found someone like me who is struggling very hard to do web application. When I started web application I did not have any one who would explain everything with myriad of details. This is why I sincerely believe that I can help lot of people who are starting afresh. Best of Luck and bear with me.


Prequisite :
----------

1. Fluency in written and spoken JAVA programming language.
2. Basic knowledge in JSP / HTML / CSS / JavaScript won't harm as well. If you don't know them go through them in  
   parallel. Its not a big deal.
3. Good working skill in Ubuntu or MAC or Windows. I will base all of my examples on Debian Ubuntu.
4. Glass of wine or vodka or beer by your side. I prefer weed. Don't forget water and foods.



Lets hit the road now. Keep Calm and CODE !



Instructions for installing Spring in Ubuntu 12.10
------------------------
PACKAGE	 INSTALLATION
------------------------
1. Update the ubuntu package >> sudo apt-get update

2. Get the IDE for development >> Latest Eclipse IDE like Kepler with JDK 1.7. J2EE is preferred instead of JDK >> 
   download the kepler from eclipse website and run the .sh file for setup.

3. Install JDK or J2EE. Set the path variable of JDK after installation >> Path is where the JAVAC resides in the   
   machine. 

   Put export JAVA_HOME = /yourJava/Installation/Directory/ in your bash file in ubuntu for setting path variable.   
   Google it if you are in confusion.
	 
   JDK installation check >> java -version

4. Install the Maven intergration for eclipse from the marketplace. >> Also install the MAVEEN in local system >> sudo 
   apt-get install maven
	 Maven install check >> mvn -version

  What is Maven ? 
  >> For now its good to understand that all the jars and packages available in the www is tracked by Maven. So 
  you can use any of the required jar for creating a boiler plate for your web application project through maven.
  It also creates a project bare bones by creating folder structure for your project.
  Its not the only functionality but now this concept should suffice.

5. Install Spring IDE from the market place . >> If it does not work find the link in google and install new software 
   from help options in eclipse.

6. Install TOMCAT server for web application development in the local machine. Also can be set up from the server    
   perspective in Kepler.

---------------------
HELLO WORLD !!
---------------------

7. Make sure that the indices for the dependencies are set to update at startup in eclipse . >> Windows > Preferences > 
   MAVEN > set the options there.

8. Create a new Maven Project and give the artifact ID and group ID.

9. Create a simple JAVA program in the project formed and see if everything works. If it works then move on to the 
   following process.

10. Open the pom.xml file and lets try to add spring jars in the project. Go to dependency and click on ADD. Select one 
    of the simpler archtype.

    What is archtype ?
    >> They are bare bones for your project. Has some simple and also sophisticated skeletel projects for good starting     point.


11. Wait !! I have just started to do this project. Give me some Time guys.. I will also try to share some information about Designing and JavaScript aspect. Mostprobally CSS3 , HTML5 and AngularJS
  
