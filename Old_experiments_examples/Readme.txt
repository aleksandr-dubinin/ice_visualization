Hello Alexandr,

Here is the notes about the data. We have talked some of them but it is always good to have a writing in your hand. 

First of all, we do not work with HOBO RF, HOBO AF, FLOWMETER and SIEMENS sections where they are available in the current code.

----------------------------------------------------------------------------------------------------------------
1. Cube Sensors >> Folder Name: CUBES

- Measurements were conducted with six cube sensors available for each case.

- For each case there is only one cube sensor file available.

- In file there are 6 sheets available which represents the each cube in related case.

- Mean Radiant Temperature values named as "Longwave Spherical Radiance (*C)" in these files.

- The locations of the cube sensor were given in the thesis of Houtart, D. (2024), page 17-Figure 3. (Location of the file is: \DATASHARE\RadiantFloor Project\Old Experiments). 

- To make everything easy I converted to the related sheet names in each file according to old positioning names named by Houtart D. Moreover, the data columns in the each file is in the same location. There is no difference in the data position in all cases of the excel files.

- Time intervals for the cube sensors is a little bit complicated. Nearly each sensor has different time interval and also that time intervals sometimes does not work properly. For instance, for the cube which is located in DC2 starting with the 1 second interval but after collecting 3 data it the interval has changed 2 seconds and again set 1 seconds. So since the time intervals are not same in the cube sensors, the amount of the collected data is not the same. 

- As you remember one sensor is collecting the time according to CEST which is not correct on that time. So, there is a one hour difference between the real time and collected. For instance in case where the real time was 23:11 the time in this sensor was 00:11. In case you will use the dates or times for the cube sensors you should be careful about it. 

- In cube sensors there are some missing data available in cases below
>> Case 3	: BC1 and AC1.
>> Case 2A	: CC1.

----------------------------------------------------------------------------------------------------------------
2. Folder Name: HOBO

- Each case have one excel file including data coming from all dataloggers. In total there are 12 hobo data loggers/ HOBO stations.

- These files include the indoor air temperature, globe temperature and air velocity values.

- The indoor air temperature values were given in B column with name as "Temp, °C (LGR S/N: 20566548, SEN S/N: 20566548, LBL: T_3a)"

- The globe temperature values were given in C column with named as Temp, °C "(LGR S/N: 20566548, SEN S/N: 20566548, LBL: T_3g)"

- The air velocity (m/s) values have already calculated by me and given in G column with named as "Air Velocity" So, you do not need any conversation or calculation as done before. You can directly use them.

- As I did in the cube sensors to help you about the locations I just changed the names of the sheets according to Houtart D.'s work.

- In HOBO Station Data there are some missing data available in cases below.
>> Case 2A: AH3 and BH3
>> Case 3: CH1

- Time interval is 1 seconds. Only in case 2A for BH3 It was 1 minute
--------------------------------------------------------------------------------------------------------------

Folder Name: MANIKIN

- For each case there is one excel file was available.

- Time interval is 1 minutes.

- The column sequence is the same as the previous dataset.

---------------------------------------------------------------------------------------------------------------

Folder Name THERMOCOUPLES

- One excel file is available for all cases. Each case is given inside excel as sheets.

- Time interval is 1 second.

- The sequence is same with the previous dataset.



