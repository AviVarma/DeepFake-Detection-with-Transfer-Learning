=== Driectory structure ===
./
|__Celeb-DF-Image-Face-Crop
|	|__Images.jpg
|
|__Celeb-DF-Image-Face-Crop-SRM
|	|__Images.jpg
|
|__Full_labels-2.txt
|
|__MobileNet with face crop.ipynb
|
|__MobileNet with face crop SRM.ipynb
|
|__ResNet with face crop.ipynb
|
|__ResNet with face crop SRM.ipynb
|
|__VGG16 with face crop.ipynb
|
|__VGG16 with face crop SRM.ipynb
|
|__Pre-process.ipynb
|
|__haarcascade_frontalface_alt.xml
|
|__README.txt

=== DATA PREPERATION ===
I used the Celeb-DF V2 dataset for this project, please download and use the "Pre-process.ipynb" 
file to create the ./Celeb-DF-Image-Face-Crop/ & ./Celeb-DF-Image-Face-Crop-SRM/ datasets mentioned
within the directory tree. (Some file path variable manipulations may be required.)

Please read the report provided for a better insight.

=== EXECUTION ===

DO NOT EXECUTE Pre-process.ipynb This was built for generating the two datasets above.
I have completed this process for you.

Before running the individual models, please make sure that the paths provided are correct for your machine I have made the relative but 
they may cause isues.
Once that is done, run the models.
