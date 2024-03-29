# About

Python scripts for WCA competition, first script is for generating certificates, second script is for generating name tags.

## HOW TO USE

It is necessary to have Python 3 installed, so you can run the script.
You need to download nametag_gui.py, certificate_gui.py and requirements.txt and put them in the same folder.
Add whatever font you like in the same folder as those three files (it needs to be .ttf).
Add picture of name tag and certificate that you want to use for competition.

### Step 1
Open terminal inside that folder and write `python3 get-pip.py` and then `pip install -r requirements.txt`.

### Step 2
Run one of the scripts with `python3 nametag_gui.py` or `python3 certificate_gui.py`.
  
### Step 3
Enter competition name or if that does not work enter url of the competition.
Enter your image name (with extension).
Enter font name (with extension).

### Step 4
Click button "Show example".
Generated image should pop up.

### Step 5
Change parameters as needed.

### Step 6
When you are done press button "Export" and all images will be exported to the folder where the scripts are located.


#### If something is not working check all parameters, because there is some invalid input.

# Preview
## Nametag generator

| ![Preview](images/nametag_generator.png) | 
|:--:| 
| *User interface of the Nametag Generator tool, which allows users to customize and generate name tags for a competition* |


| ![Preview](images/nametag_example.png) | 
|:--:| 
| *Preview of a generated nametag* |

## Certificate generator


| ![Preview](images/certificate_generator.png) | 
|:--:| 
| *User interface of the Certificate Generator tool, which allows users to customize and generate certificates for a competition* |


| ![Preview](images/certificate_example.png) | 
|:--:| 
| *Preview of a generated certificate* |
