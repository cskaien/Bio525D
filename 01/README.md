* Start your VM in virtualbox	   	   
* Open “firefox" under the *Activities* menu	   
* Navigate to www.zoology.ubc.ca/~yeaman/bioinformatics 
* Right click on the link that says “data_cleaning_and_manipulation.tbz” and choose “copy link location” [for mac, this should be command-mouseclick; not sure about PC keyboard]	   
* Open “Terminal" under the *Activities* menu, type “wget“ and then paste in the link that you copied. Alternatively, type in the link yourself and add the filename at the end. This will download today’s dataset onto your virtual machine.	   
* Type `tar –xjvf data_cleaning_and_manipulation.tbz`. This will unpack the archive and create a new directory. Navigate to the directory (type `cd data_cleaning_and_manipulation`) and open the README file there, and follow the directions. You can open the README file in a more friendly text editor by choosing the “files” icon from the activities menu and opening the README file there.	   