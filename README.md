<img width="719" height="138" alt="kép" src="https://github.com/user-attachments/assets/f92f97b7-5a12-4908-9961-0d44ec07607f" />

Do you hate to open Fusion360 just to generate gcode for two holes? I don't know about you, but I do hate that.
I wanted it to work like on "big guy's" machines where you have "canned cycles" - predefined scripts embedded into Gcode where you can quickly spit out basic operations. This is not only convenient but converts your CNC mill or router into a "fast use" tool that you can reach to. Makes a difference in the workshop.

### PROJECT IS METRIC
However, you are more than welcome to remix it to imperial. Shouldn't be hard.

### DISCLAIMER
It is easy to crash your machine in a thousand ways. Please always do dry runs if you are not familiar with gcode. I cannot take responsibility for what your machine does with this gcode.  
If you download this project you accept this simple term.
  
### DOWNLOAD
Download the latest zip from the releases:  
https://github.com/dansity/GRBL-MultiTool/releases/latest  
  
Unzip locally, then open GRBL_Multi-Tool.html file.  
Use your preferred G-Code sender to run cycle.  
  
### Currently supported operations:

- Facing / Skimming
- Rectangular pocket
- Rectangular cutout
- Circle pocket
- Circle cutout
- Drilling holes

### MACHINE COMPATIBILITY
The generated gcode is very basic in the sense that it only uses G0, G1, G3 operations.  
Most machines can digest these so chances that you can run it on yours are high (regardless of the brand of the conroller).  
Feel free to edit the javascript to match your machine, it is rather simplistic.

### What's inside?
Project is made using HTML and Javascript.  
It will run on any device with a browser.  
It will run without internet**.  
It will not terrorize you for money.  
Its free, open and yours forever.  

**The project will run without internet, however some styling elements are downloaded on the fly.  
Without internet connection you will not see the 3D preview and may miss some fonts and such. Will still work tho.

### What external libraries used?
3D viewer: https://github.com/xyz-tools/gcode-preview  
CSS and Styling: tailwindcss.com

### Lovely interface
<img width="1298" height="873" alt="kép" src="https://github.com/user-attachments/assets/c761dd0d-a6fd-4ab5-b94f-ac6e05394347" />  
Now with tooltips:
<img width="933" height="868" alt="image" src="https://github.com/user-attachments/assets/c489da74-5589-4d03-9f92-72ca9e861cbc" />

### What's next? - Roadmap

- Boring toolpath generator (similar to the current drilling) but with a helical path
- Create a custom CSS file and free ourselves from tailwindcss without sacraficing function and simplicity
