# Electoral College Light Analysis

Infographic representing relative vote weight by state (calculated by registered voters / electoral votes). Created with Microsoft Excel

Steps for re-creation are obtaining data (1) and creating visualization (2)

Sources:<br/>
[Voters per state](https://worldpopulationreview.com/state-rankings/number-of-registered-voters-by-state)<br/>
[Electoral votes per state](https://state.1keydata.com/state-electoral-votes.php)<br/>
[State lookup table](https://www.extendoffice.com/documents/excel/3332-excel-convert-state-name-to-abbreviation.html)<br/>

## Obtaining and Manipulating Data

Under construction*

----------------

Step 1: Getting the data from the web!

I've already found the necessary websites, so all that's left to do is get the information that they hold into our Excel file. When attempting to get data from the web, I always like to start out with Excel's nice Get Data --> From Other Sources --> From Web:

![pic_1](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/Project_Pics/pic_1_b.png)

Simply [paste in the website name](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/Project_Pics/pic_2_b.png), hit okay, and you should be met with this window:

![pic_3](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/Project_Pics/pic_3_b.png)

It looks like Table 0 is what we want, so that's what we select. It's good practice to check out your query in the query editor, so while this pull is simple and we could simply hit "Load" from here, let's instead hit "Transform Data" and open up that query editor:

![pic_4](https://github.com/Pressed-In/Electoral_College/blob/main/Project_Pics/pic_4_b.png)

Everything looks good, so let's hit that "Close and Load" button, and see that we've successfully loaded voter data for all 50 states:

![pic_5](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/Project_Pics/pic_5_b.png)

Awesome!

Let's get data from the web from our 2nd website, [pasting in the appropriate URL](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/Project_Pics/pic_6_b.png). This time, it looks like [Table 1 is what we need](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/Project_Pics/pic_7_b.png), and we repeat the same "Transform Data" process as with the first data table.

Onto the 3rd and final [website](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/Project_Pics/pic_8_b.png), and we're met with something new. Our headers are included in the data themselves:

![pic_8](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/Project_Pics/pic_9_b.png)





## Creating Visualization

Under construction

## Infographic

![Infographic](https://raw.githubusercontent.com/Pressed-In/Electoral_College/main/electoral_weight_viz.png)
