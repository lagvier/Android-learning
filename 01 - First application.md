- [x] Install the Android studio
   - Download [AndroidStudio](https://developer.android.com/)
   - Install the application by following the installation propmpts

- [ ] Java fundamentals
  * Java applications have structure sample below and just like C/C++ programs the _main ()_ routine is the first to be executed. The files must be saved with with the convention _classname.java_ such that the sample program below should be saved as _HelloWorld.java_
      ``` 
      1: class HelloWorld {
      2: public static void main (String args[]) {
      3:     System.out.println(“Hello World!”);
      4:     }
      5: }
    ```
  
  * Java programs are compile by the _javac_ command such that the below sample is compiled: _java _HelloWorld.java_
  * Run the compiled program with _java_ eg _java HelloWorld_. Note that there is no extension when running the program.

- [x] Create first app
  * Start Android studio
  * __New project screen__: Give your app a name say,  _MyFirstApp_. Leave all other options at default and click _Next_
  * __Target devices__: Leave the default settings and click _Next_. For the minimum Android SDK to be supported by the application
  * __Activity__: Select _Empty activity_ and click _Next_. It more represents a screen
  * __Customize activity__: Leave the default settings and click _Finish_
  * __Create Virtual Device__:
     - Click on AVD Manager icon and click _Create Virtual Device_ (You can cl
     - Choose a device and click _Next_
     - Choose version and click _Next_
     - Leave the AVD name default information and click _Finish_
     
  * __Launch Virtual Device__:
     - Click on run app (green button) on the toolbar tap
     
  * __Test with your Device__:

- [ ] App Layout


- [ ] Properties information
 * __ID__: IDs should be named by the format objecttype_information eg text_value represents an id for a text field called _text_
 * __Layouts(heigh/width)__: wrap_content (the size of the object depends on the size of the label), _match_parent_ (use the whole size of the current screen section*)


- [x] Access __.apk__ of your app
  * Get the __app_debug.apk__ From: _AndroidStudioProjects_ > _MyFirstApp_ > _App_ > _Build_ > _outputs_ > _apk_
