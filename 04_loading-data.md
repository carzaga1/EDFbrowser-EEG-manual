# Loading EDF Files and Montages


I have added an example EEG (sample.edf-file*) to the research drive

  *this sample.edf file was obtained from [EDFviewer](https://kostasrotas.mysch.gr/edfviewer/samples.zip "EDF Viewer") which contains no actual data from KISPI and/or USZ

## Loading an EDF File
> 1. Navigate to the following path file **TO DO: enter path file** on your computer
> 2. Double click on the .edf file contatined in the folder, this should automatically launch EDFBrowser
        
  You should see the following on your computer screen:
  ![EDFBrowserLaunch](..images\edf-launch.png "EDFLaunch")
  <figcaption>
  You might see an annotations loading box window occasionaly, if this takes longer than 30 sec. you can go ahead and close the window
  </figcaption>
  
       **TO DO: resize (make larger) gif of annotations window**

[code below works/straight forward markdown]: #
<!-- ![Launching EDFviewer gif](edflaunch.webp "EDFLaunch") -->

<figure>
    <img src="C:\Users\c_arz\Documents\KISPI\Burst_Suppression_Project\EDFbrowserDocumentation\EDFlaunch.gif"
         alt="EDFlaunch.gif"
         width="639" height="360">
</figure>

<video width="720" height="405" autoplay controls>
    <source src="C:\Users\c_arz\Documents\KISPI\Burst_Suppression_Project\EDFbrowserDocumentation\EDFlaunch.mp4" 
    type="video/mp4">
</video>
       
## Loading Montages

Now that the file is loaded with the raw EEG signals, one needs to create a montage for them to actually be viewable on the screen.  

The creation of Montages is explained in the following documentation **TO DO: add link to 'Creating Montage Section of book'**  

I have already created some of the standard montages based on the American Clinical Neurophysiology Society [ACNS](https://www.acns.org/UserFiles/file/EEGGuideline3Montage.pdf "ACNS") EEG guidelines.  

This section will walk through how to load and save the previously created montages and additional tips on 'binding' as keyboard hotkeys

>  1. The created montage files are located in the following folder **TO DO: Add path to montages location**
>  2. With EDFviewer open and EEG file loaded select the '*Montage*' tab and select '*Load*'
>  3. Navigate to the **TO DO: add Montage file path**
>  4. Select the montage file

**TO DO: ADD gif/vid of selecting montage file**