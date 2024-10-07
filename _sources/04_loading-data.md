# Loading EDF Files and Montages


I have added an example EEG (sample.edf-file*) to the research drive

  *this sample.edf file was obtained from [EDFviewer](https://kostasrotas.mysch.gr/edfviewer/samples.zip "EDF Viewer") which contains no actual data from KISPI and/or USZ

## Loading an EDF File
> 1. Navigate to the following path file **TO DO: enter path file** on your computer
> 2. Double click on the .edf file contatined in the folder, this should automatically launch EDFBrowser
        
  You should see the following on your computer screen:
  ![EDFBrowserLaunch](images\edf-launch.png "EDFLaunch")
  <figcaption>
  You might see an annotations loading box window occasionaly, if this takes longer than 30 sec. you can go ahead and close the window
  </figcaption>


[code below works/straight forward markdown]:#
<!-- ![Launching EDFviewer gif](edflaunch.webp "EDFLaunch") -->

[code below works/straight forward html]:#
<!--
<figure>
  <img src="images\edf-launch.gif"]
          alt="edf-launch.gif"
          width="639" # height="360">]
 </figure>
 -->

<video width="720" height="405" autoplay controls>
    <source src="images\edf-launch.mp4" 
    type="video/mp4">
</video>
       
## Loading Montages

Now that the file is loaded with the raw EEG signals, one needs to create a montage for them to actually be viewable on the screen.  

The creation of Montages is explained in the following documentation  **TO DO: add link to 'Creating Montage Section of book'**  

I have already created some of the standard montages based on the American Clinical Neurophysiology Society [(ACNS)](https://www.acns.org/UserFiles/file/EEGGuideline3Montage.pdf "ACNS") EEG guidelines.  

This section will walk through how to load and save the previously created montages and additional tips on 'binding' as keyboard hotkeys

>  1. The created montage files are located within the created 'Montages' folder (e.g. "C:\Users\Desktop\Archemides_BSUPP\Montages")
>  2. With EDFviewer open and EEG file loaded select the '**Montage**' tab and select '**Load**'
>  3. Navigate to the Montages folder
>  4. Select the montage file

<video width="720" height="405" autoplay controls>
    <source src="images\edf-montages.mp4" 
    type="video/mp4">
</video>


```{tip}
To add a montage as a **hot-key** select **Montage**->**Edit key-bindings for Montages** then select an available (blank) desired hot-key (e.g. F1:,F2:, etc.) click **Edit** finally select the montage file you want to bind.

Now the next time you load and want to view an EEG file you can simply click the bounded hot-key with your desired montage.
```


