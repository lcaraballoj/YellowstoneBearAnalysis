# YellowstoneBearAnalysis
This is a project to work on analytic skills. It uses information gathered by the Interagency Grizzly Bear Committee's annual reports.

All of this data is from the <a href="https://igbconline.org/grizzly-bear-study-team/">Interagency Grizzly Bear Study Team (IGBST)</a>. These annual reports are the results of grizzly bear research and monitoring in the Great Yellowstone Ecosystem (GYE) by the Interagency Grizzly Bear Study Team. The annual reports start in 1997 and the most recently published report the investigation from 2022.

The first step of analyzing this data was taking screen shots of the tables found in "Bear Monitoring and Population Trend" specifically Table 1 and Table 3. Table 1 highlights all of the grizzly bears captured in the GYE for that year and consists of the bear's identification, sex, age, date it was captured, general location of the capture, capture, type, relase site, and which organization handled the capture. Table 3 highlights all of the bears radiomonitored, any offspring of note, and whether the radiomonitor is still opporational. To populate a data set I first needed to get the data into a csv file. I did this by taking screenshots of the table and using Excel to export the data from the screenshots. There was some manual cleanup and verifcation that needed to happen in Excel before being able to export it to a csv and explore the data more. This was a tedious process and was only done becuase I could not find an already available csv file of all the data that was included in the tables. I found that as the years went on Excel had a harder time converting the pictures of the tables to usable data so there was a lot of manual entry. Becuase of this there is clearly some room for human error, both on my side and becuase of the change of naming conventions in the data set. Most of this will be identified in the data exploration phase and get cleaned up in the data cleansing phase. 

Some of the basic cleanup done in Excel includes:
- Making sure Excel imports the data correctly from the images
- Making sure naming conventions are kept
    - 2018 IGBST uses the form *Removed (#209090)* for the **Release Site** column which is not used anywhere else. In fact there is no removal number after 2017
    - Sometimes the hyphen gets lost in *PY-WY*

The CSV files in this folder is the result of that initial cleanup.