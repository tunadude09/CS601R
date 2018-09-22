Required Libraries:
Python
Anaconda 2
Opencv
Pillow

Required Directories:
You need to download leeds butterfly and birds data sets. Place leeds in "lib" fold next to your ipynb, then put "leedsbutterfly" and "bird_images" folders in this lib folder. See import paths at the top of Features_And_Learning.ipynb. 


How to run:
Basically these are all jupyter notebooks and should be run in that environment. Some things are hard coded, but it will run out of the box for the 10 class butterfly identification task. Just run in order. Actually one cell, the one with the "classification_accuracy" method outside the class, won't run properly until the cells at the bottem of the ipynb are run first. I didn't want to place the code higher up as it obfiscated the results. For displaying visual words the run-time was taking forever so I split my notebook a few different ways to do multiple things at once. In Features_And_Learning_Visual_Words.ipynb I largely run the one on it's own then access it's inner features etc in order to quickly experiment and display with outside methods. If you run the notebook in order ot should work fine. I did hardcode some things here and there so it might not work for certain tasks without commenting/uncommenting. I finished the masking extra credit and started on the fisher vector extra credit. The Fisher vector ipynb is mostly existing code from other libraries that I've modified to work with our dataset. I'm not sure how much of it counts towards the extra credit though as I didn't include it in the project pipeline but just left it as a standalone model.

That's it, thanks, this was a fun project. Learned a lot.


