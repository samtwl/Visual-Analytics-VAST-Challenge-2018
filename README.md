![1000px-Pitiful_Pipit](https://user-images.githubusercontent.com/50171205/59179798-bd126c80-8b95-11e9-9d68-c11edd4c64fd.png)

# Visual-Analytics-VAST-Challenge-2018
This repository contains the exploratory data analysis on the VAST challenge 2018 data. The link to the challenge is: http://www.vacommunity.org/VAST+Challenge+2018+MC1

## Overview
The VAST Challenge analysis results from 2017 suggested that the Kasios Furniture manufacturing company may have contributed to the decline in number of nesting Rose-Crested Blue Pipit from the Boonsong Lekagul Nature Preserve. However, Kasios dismissed the analysis and provided a set of Pipit bird calls with locations of where they were recorded to establish their claim that the analysis result was flawed.

Perhaps the characteristics of bird location in the Preserve and Kasios’ bird call recordings could provide more insight into the real situation.

## Mini Challenge 1 Background
View the interactive Tableau design here: https://public.tableau.com/profile/samuel.tong#!/vizhome/WorkingFile080718/PitifulPipitsVisualizingBluePipitsPlight

### 1. The Dataset
![The Dataset](https://user-images.githubusercontent.com/50171205/59179633-39588000-8b95-11e9-801b-f8c0e1729c60.png)

(a) File ID: Index to the file names in the ALL BIRDS file collection 
(b) English_name: Common English name for the particular bird 
(c) Vocalization_type: The kind of bird sound it is: a call, a song, or some other particular sound 
(d) Quality: A score A, B, C, D, or E. These provide a qualitative measure of the quality of the bird sound, e.g., purity, lack of background noise, and so on 
(e) Time: Time of capture of the sound 
(f) Date: Date of capture of the sound 
(g) X: the X coordinates on the enclosed map of where the sound was recorded 
(h) Y: the Y coordinates on the enclosed map of where the sound was recorded

### 2. The Map
![The Map](https://user-images.githubusercontent.com/50171205/59179659-555c2180-8b95-11e9-869a-fe64eb642855.png)

The map “Lekagul Roadways 2018” is a 200 x 200 pixel map of the Preserve, with general indications of roadways through the site

### 3. The Alleged Dumping Site
![500px-The_Alleged_Dumping_Site](https://user-images.githubusercontent.com/50171205/59179682-6c9b0f00-8b95-11e9-9606-173da1b2bb10.png)

The alleged dumping site for the Kasios waste products was centered around coordinates (148,159).

### 4. Total Number of Birds Recorded
![Total_Number_of_Birds_Recorded](https://user-images.githubusercontent.com/50171205/59179709-7f154880-8b95-11e9-91a6-846fcc4cd57d.png)

### 5. Time Period of Bird Vocalizations Recorded
![1000px-Time_Period_of_Bird_Vocalizations_Recorded](https://user-images.githubusercontent.com/50171205/59179731-8dfbfb00-8b95-11e9-942b-3fce20d0da86.png)

### 6. Total Number of Vocalization of each Vocalization Type
![Total_Number_of_Vocalizations_of_each_Vocalization_Type](https://user-images.githubusercontent.com/50171205/59179756-9d7b4400-8b95-11e9-995d-005fa714d49b.png)

### 7. Number of Vocalization by Quality and Vocalization Type
![500px-Number_of_Volcalization_by_Quality_and_Vocalization_Type](https://user-images.githubusercontent.com/50171205/59179779-ae2bba00-8b95-11e9-85de-66ec4f257e0d.png)

## Methodology
### To Examine Blue Pipit Spatial Distribution Prior to and After Alleged Dumping

| Description | Illustration |
| --- | --- |
| <br>**1. Alleged Dumping Site**</br> <br>The location of the alleged dumping site was indicated as (148, 159). By marking the location on the map, it allows us to identify the spatial-temporal patterns of the affected Rose-Crested Blue Pipits in the Preserve prior to and after the alleged dumping of the process waste.</br> | ![The_Alleged_Dumping_Site](https://user-images.githubusercontent.com/50171205/59179901-08c51600-8b96-11e9-8cc6-cdc41fc861c4.png) |
| <br>**2. Time Period (Years) and Alleged Date of Dumping**</br> <br>The number of months taken to record the vocalization of the birds in the Preserves over the years were not consistent. Only some years have recordings for all months – Year 2009 and 2011 to 2017.</br> <br>Additionally, in accordance with the details obtained from VAST Challenged 2017, the alleged date of the chemical dumping was on 15th February 2015 as indicated in the orange arrow below:</br> ![1 2_Alleged_Date_of_Dumping](https://user-images.githubusercontent.com/50171205/59179977-42961c80-8b96-11e9-8d88-80113f757cc7.png) <br>Therefore, in order to facilitate in our analysis of the spatial-temporal patterns of the birds in the Preserve, we will use only year 2011 to 2017 for our data visualization of the distribution of birds prior to the dumping and after the dumping.</br> | ![1000px-Time_Period_of_Bird_Vocalizations_Recorded](https://user-images.githubusercontent.com/50171205/59179731-8dfbfb00-8b95-11e9-942b-3fce20d0da86.png) |
| <br>**3. Geographical Distribution of Rose-crested Blue Pipit from 2011 to 2017**</br> <br>From 2011 to 2017, we want to identify the spatial distribution of the Rose-Crested Blue Pipits by plotting the location of where the recordings were taken over time.</br> | ![1 3  Geog Dist of Blue Pipits from 2011 to 2017](https://user-images.githubusercontent.com/50171205/59180226-f1d2f380-8b96-11e9-9b4e-cc8cce1f59f3.gif) |
| <br>**4. Number of Rose-Crested Blue Pipit Recorded from 2011 to 2017**</br> <br>The number of Rose-crested Blue Pipit recorded peaked at 45 in 2015, just when the dumping took place. Thereafter, the number of Rose-crested Blue Pipit recorded dropped to 27 in 2016 and to 16 in 2017.</br> | ![1 4 _Number_of_Rose-Crested_Blue_Pipit_Recorded_from_2011_to_2017](https://user-images.githubusercontent.com/50171205/59180297-247cec00-8b97-11e9-8a77-a9bb225b65b4.png) |

### To identify distribution of Blue Pipits by Vocalization Type from 2013 to 2015
| Description | Illustration |
| --- | --- |
| <br>**1. Vocalization Type**</br> <br>With multiple types of vocalizations, we want to focus mainly on the two major categories of vocalization, which is produced by the vocal organ of the birds – Call and Song.</br> <br>Additionally, we will also exclude the Vocalization Type “call, song”, as we want to be specific about which vocalization type we are analysing.</br> | ![1000px-2 1_Vocal_type](https://user-images.githubusercontent.com/50171205/59180370-5a21d500-8b97-11e9-9056-b86de459ba52.png) |
| <br>**2. Distribution of Blue Pipits by Vocalization Type from 2011 to 2017**</br> <br>We want to plot the distribution of Blue Pipits by Vocalization Types “Call” and “Song” from 2011 to 2017 to examine if there are any significant spatial pattern relating to the alleged process waste dump in 2015.</br> | ![1000px-2 2 _Distribution_of_Blue_Pipits_by_Vocal_Type_from_2011_to_2017](https://user-images.githubusercontent.com/50171205/59180403-74f44980-8b97-11e9-81d5-618a040b5927.png) |

### To Compare Spatial Distribution Between Blue Pipits and Other Birds
| Description | Illustration |
| --- | --- |
| <br>**1. Geographical Distribution of All Birds from 2011 to 2017**</br> <br>From 2011 to 2017, we can see that there are typically four major nesting areas for all birds – North-East, represented by the Green rectangle, North-West, represented by the Red rectangle, South-West, represented by the Purple rectangle, and South-East, represented by the Blue rectangle.</br> <br>We want to map out the nesting areas for the other birds to be compared against the nesting area for the Blue Pipits to identify any possible spatial relationship between them.</br> | **Spatial Distribution of All Birds from 2011 to 2017:** ![3 1_Distribution_of_all_birds_2011-2017](https://user-images.githubusercontent.com/50171205/59180541-ce5c7880-8b97-11e9-98d8-96f7c61d8b2d.gif) **Four Major Nesting Areas:** ![3 1_4_areas_of_geog_distribution](https://user-images.githubusercontent.com/50171205/59180600-ee8c3780-8b97-11e9-8990-15ebfab75cb7.png) |
| <br>**2. Number of All Birds Recorded from 2011 to 2017**</br> <br>Besides understanding the spatial distribution of all birds as compared to the spatial distribution of the Blue Pipits, we also want to know the population size of the birds in comparison with the population size of Blue Pipits for the chosen year of observation.</br> | ![1000px-3 2_No _of_all_bird_recroded_from_2011_to_2017](https://user-images.githubusercontent.com/50171205/59180666-1f6c6c80-8b98-11e9-929c-03a6146da074.png) | 

### To Compare Test Blue Pipits Locations Against Actual Blue Pipits Locations
| Description | Illustration |
| --- | --- |
| <br>**1. Distribution of Rose-Crested Blue Pipits Recording Locations**</br> <br>In order to back up their claim that the Rose-crested Blue Pipits population has not reduced, Kasios has provided a set of Pipit bird calls, recently recorded across the Preserve, with locations of where they were recorded.</br> <br>There are 15 test recordings in total, with the spatial distribution of where these recordings were allegedly plotted onto the graph to the right.</br> | ![1000px-4 1_Dis_of_Blue_Pipits_Recording_Locations](https://user-images.githubusercontent.com/50171205/59180715-3c08a480-8b98-11e9-9432-dc76fc1a427d.png) |

### To Select Samples of Actual Recordings for Analysis
| Description | Illustration |
| --- | --- |
| <br>**1. Number of Records by Quality and Vocalisation Type**</br> <br>There are 51 recordings of Rose-crested Blue Pipits that are of grade A. 29 of them are calls, while 22 of them are songs.</br> <br>To ensure that we will be able to accurately analyse the patterns of the actual recordings to be compared against that of the Test Recordings, it is essential that we only analyse recordings that are of Grade A.</br> | ![1000px-5 1 _No _of_Records_by_Quality_and_Vocal_Type](https://user-images.githubusercontent.com/50171205/59180765-5e022700-8b98-11e9-86e8-235a6c8b645d.png) |
| <br>**2. Distribution of Rose-crested Blue Pipits Grade A Song and Call Recordings**</br> <br>Upon plotting the distribution of the Grade A song and call actual recordings, we want to pick samples of actual recordings to be analysed and compared against the Test Recordings. This can be done by visualising where each of the Grade A recordings are located, and to pick those recordings that are located closest to the Test Recordings. Additionally, in order to ensure that we will be able to analyse if the sound waves of the test recordings are similar to the sound waves of the actual recordings, we want to take into account of possible environmental attributes that could lead to a difference in the patterns of recordings in each area. Therefore, we would like to first segregate the recordings into different areas as shown on the right.</br> <br>Since the Test Recordings have no indication of vocalization type – Whether they are song or call vocalization, we will pick the maximum of 25% samples of the population in each coloured zones, or the total population in each coloured zones if the population is less than or equals to 5.</br> <br>The selected actual recordings will thus be segregated into the following six categories:</br> <br>1.	Green Song</br> <br>2.	Green Call</br> <br>3. Red Song</br> <br>4.	Red Call</br> <br>5.	Purple Song</br> <br>6.	Purple Call</br> <br>The designated colours attached to each recording category corresponds with the coloured areas to the right.</br> | ![1000px-5 2 _Dist_of_Blue_Pipit_Grade_A_Song](https://user-images.githubusercontent.com/50171205/59180856-8c800200-8b98-11e9-8668-557cefaab99b.png) ![1000px-5 2 _Dist_of_Blue_Pipit_Grade_A_Call](https://user-images.githubusercontent.com/50171205/59180943-bcc7a080-8b98-11e9-8c31-1240a4139680.png) |

### To Determine Authenticity of Test Recordings: Analyse Patterns Between Test Recordings and Actual Recordings
| Description | Illustration |
| --- | --- |
| <br>**1. Samples of Actual Song and Call Recordings:**</br> <br>Upon selecting our samples of actual recordings, we will attempt to visualise these audio files by utilising the ‘tuneR’ package in R.</br> | **For Green Song:** ![Green Song 1](https://user-images.githubusercontent.com/50171205/59182164-a111c980-8b9b-11e9-8281-dc4a495369ab.png) ![Green Song 2](https://user-images.githubusercontent.com/50171205/59182166-a1aa6000-8b9b-11e9-9bb8-d1c9cc43c98d.png) ![Green Song 3](https://user-images.githubusercontent.com/50171205/59182173-a3742380-8b9b-11e9-9027-17a80233edc3.png) ![Green Song 4](https://user-images.githubusercontent.com/50171205/59182176-a4a55080-8b9b-11e9-9967-e8da99a04c75.png) ![Green Song 5](https://user-images.githubusercontent.com/50171205/59182177-a4a55080-8b9b-11e9-865e-1fe877491f61.png) |
| | **For Green Call:** ![Green Call 1](https://user-images.githubusercontent.com/50171205/59181835-ce11ac80-8b9a-11e9-9f80-a580ebb44340.png) ![Green Call 2](https://user-images.githubusercontent.com/50171205/59181848-d4078d80-8b9a-11e9-9409-46082ba6bef8.png) ![Green Call 3](https://user-images.githubusercontent.com/50171205/59181852-d5d15100-8b9a-11e9-8f71-c1fccb72f5a5.png) ![Green Call 4](https://user-images.githubusercontent.com/50171205/59181853-d5d15100-8b9a-11e9-9da4-858dcb5ad60e.png) ![Green Call 5](https://user-images.githubusercontent.com/50171205/59181854-d669e780-8b9a-11e9-9110-6267751840b3.png) |
| | **For Red Song:** ![Red Song 1](https://user-images.githubusercontent.com/50171205/59182109-7cb5ed00-8b9b-11e9-8cf3-8d45b2607052.png) ![Red Song 2](https://user-images.githubusercontent.com/50171205/59182110-7d4e8380-8b9b-11e9-8a43-27e7286d0d20.png) ![Red Song 3](https://user-images.githubusercontent.com/50171205/59182112-7d4e8380-8b9b-11e9-9034-7f1056826dbc.png) |
| | **For Red Call:** ![Red Call 1](https://user-images.githubusercontent.com/50171205/59182376-2f864b00-8b9c-11e9-81a1-7812138a8c51.png) ![Red Call 2](https://user-images.githubusercontent.com/50171205/59182377-2f864b00-8b9c-11e9-9be1-312cc17b13c2.png) ![Red Call 3](https://user-images.githubusercontent.com/50171205/59182378-2f864b00-8b9c-11e9-9f3f-21b720815f61.png) |
| | **For Purple Song:** ![Purple Song 1](https://user-images.githubusercontent.com/50171205/59182430-53e22780-8b9c-11e9-8d99-0698fe046b21.png) ![Purple Song 2](https://user-images.githubusercontent.com/50171205/59182432-53e22780-8b9c-11e9-839f-fa876c4e18bf.png) |
| | **For Purple Call:** ![Purple Call 1](https://user-images.githubusercontent.com/50171205/59182441-593f7200-8b9c-11e9-8121-c5c7fca65e0f.png) |
| <br>**2. Samples of Test Recordings:**</br> <br>Additionally, we will visualise all Test Recordings, to be compared with the selected samples of actual grade A song and call recordings in each segment. </br> | **Green Test Recordings:** ![Test Green 1](https://user-images.githubusercontent.com/50171205/59182567-ac192980-8b9c-11e9-8f0d-cfaa91870fba.png) ![Test Green 6](https://user-images.githubusercontent.com/50171205/59182571-ad4a5680-8b9c-11e9-857a-c4f066948a03.png) ![Test Green 11](https://user-images.githubusercontent.com/50171205/59182572-ad4a5680-8b9c-11e9-8d64-8df29ae5d01e.png) ![Test Green 15](https://user-images.githubusercontent.com/50171205/59182573-ad4a5680-8b9c-11e9-9716-746c57415af6.png) |
| | **Red Test Recordings:** ![Test Red 2](https://user-images.githubusercontent.com/50171205/59182639-d2d76000-8b9c-11e9-9a1a-b4da9fc6669a.png) ![Test Red 3](https://user-images.githubusercontent.com/50171205/59182641-d36ff680-8b9c-11e9-855b-4e04f2b9c0ec.png) ![Test Red 4](https://user-images.githubusercontent.com/50171205/59182642-d36ff680-8b9c-11e9-9c44-9f97c458de25.png) ![Test Red 7](https://user-images.githubusercontent.com/50171205/59182643-d4088d00-8b9c-11e9-93b0-35e43b51cdcb.png) ![Test Red 9](https://user-images.githubusercontent.com/50171205/59182645-d4a12380-8b9c-11e9-8769-269220887002.png) ![Test Red 13](https://user-images.githubusercontent.com/50171205/59182646-d4a12380-8b9c-11e9-8c14-895f7c40afe2.png) ![Test Red 14](https://user-images.githubusercontent.com/50171205/59182647-d539ba00-8b9c-11e9-81e1-63379cfde8d2.png) |
| | **Purple Test Recordings:** ![Test Purple 5](https://user-images.githubusercontent.com/50171205/59182708-f4384c00-8b9c-11e9-8a99-0deb13ec2389.png) ![Test Purple 8](https://user-images.githubusercontent.com/50171205/59182715-f5697900-8b9c-11e9-9880-8fd2da3c1a40.png) ![Test Purple 10](https://user-images.githubusercontent.com/50171205/59182716-f6020f80-8b9c-11e9-9a37-b3acf91a0423.png) ![Test Purple 12](https://user-images.githubusercontent.com/50171205/59182718-f6020f80-8b9c-11e9-9862-d8c11fa14679.png) |

## Dashboard Design

### 1.Blue Pipit Spatial Distribution Prior and After Alleged Dumping
![Dashboard - 1](https://user-images.githubusercontent.com/50171205/59182789-31044300-8b9d-11e9-8d07-df254756fafb.png)

### 2.Distribution of Blue Pipits by Vocalization Type from 2013 to 2015
![Dashboard - 2](https://user-images.githubusercontent.com/50171205/59182843-5c872d80-8b9d-11e9-9880-add44b4fc907.png)

### 3.Comparison of Spatial Distribution Between Blue Pipits and All Other Birds
![Dashboard - 3](https://user-images.githubusercontent.com/50171205/59182844-5e50f100-8b9d-11e9-839f-f3501da80856.png)

### 4.Comparison of Test Blue Pipits Locations Against Actual Blue Pipits Locations
![Dashboard - 4](https://user-images.githubusercontent.com/50171205/59182845-5e50f100-8b9d-11e9-8f84-4692e945abff.png)

### 5. Selecting Samples of Actual Recordings for Analysis
![Dashboard - 5](https://user-images.githubusercontent.com/50171205/59182846-5ee98780-8b9d-11e9-9eb6-0ed08bb9e5e5.png)

### 6. Determining Authenticity of Test Recordings: Analysing Patterns Between Test Recordings and Actual Recordings
![Dashboard - 6 1](https://user-images.githubusercontent.com/50171205/59182847-5ee98780-8b9d-11e9-94a2-8aa065b84c2a.png)
![Dashboard - 6 2](https://user-images.githubusercontent.com/50171205/59182850-5f821e00-8b9d-11e9-9767-ee56bef718c1.png)
![Dashboard - 6 3](https://user-images.githubusercontent.com/50171205/59182852-601ab480-8b9d-11e9-8e5a-20ef2041b715.png)
![Dashboard - 6 4](https://user-images.githubusercontent.com/50171205/59183072-da4b3900-8b9d-11e9-97e2-da0e802bfa72.png)
![Dashboard - 6 5](https://user-images.githubusercontent.com/50171205/59182856-60b34b00-8b9d-11e9-9c21-a6363fca2c01.png)
![Dashboard - 6 6](https://user-images.githubusercontent.com/50171205/59182857-614be180-8b9d-11e9-89c7-c0fd448e322d.png)

## Insights

| Patterns | Visualization |
| --- | --- |
| <br>**1. Number of Rose-crested Blue Pipit Recorded from 2011 to 2017**</br> <br>From 2011 to 2014, we can clearly see two distinct nesting areas for the Rose-crested Blue Pipit. The first nesting area is located in the north-eastern area of the map (First Nest), where the alleged dumping site is located at, and the second nesting area is located just south-west of the first nesting area (Second Nest).</br> <br>In 2015, when the alleged dumping took place, the concentration of Rose-crested Blue Pipit in the First Nest seemed to diminished completely. However, we can see an overwhelmingly increase in number of Rose-crested Blue Pipits in the Second Nest. Thereafter, the number of Rose-crested Blue Pipits in the Second Nest decreased to 27 in 2016 and 16 in 2017, as reflected from the line graph.</br> <br>This observations can be explained by the following: Upon losing a habitat, the Rose-Crested Blue Pipit had to migrate to the second habitat where there could have been an increase in competition for food and other resources. Therefore, this could thus lead to a sudden drop in the population size of the Rose-Crested Blue Pipit.</br> | ![1 1 - insights](https://user-images.githubusercontent.com/50171205/59183332-55acea80-8b9e-11e9-9de6-983d3859872d.png) |
| <br>**2. Distribution of Blue Pipits by Vocalization Type from 2013 to 2015**</br> <br>According to Marler. P (2004), bird songs and calls differ in terms of their application. While songs serve as a mean for birds to attract potential mates, calls on the other hand mostly serve as distress warnings to other birds.</br> <br>In this case, we can see that in 2013 at the First Nest, there are a mixture of songs and calls by the Blue Pipits. However, in 2014, prior to the alleged process waste dumping in 2015, the Blue Pipits started to exhibit more calls, and no songs were recorded in the First Nest. Subsequently, the Blue Pipits migrated to the Second Nest in 2015. Therefore, the observation that only calls were recorded in the First Nest in 2014 could point to the fact that activities related to the process waste dumping could have taken place in 2014 prior to the actual dumping in 2015. Perhaps a reconnaissance was being carried out to determine if the First Nest was a suitable place to dispose the process waste by Kasios.</br> | ![2 1 - insights](https://user-images.githubusercontent.com/50171205/59183333-56458100-8b9e-11e9-9aff-6285a1df6fb6.png) |
| <br>**3. Comparing Distribution of Blue Pipits Against Other Birds from 2011 to 2017**</br> <br>With reference to point 1 above, where Blue Pipits were seen migrating from their north-eastern nesting area to the south-west after the alleged dumping incident in 2015, it can be observed that despite having little to no competition for resources in that area, no other birds were seen migrating north-east to take over the north-eastern nesting area in 2015 or after.</br> <br>Interestingly, we can also visualize the migration of the Blue Pipits to the south-west of their original north-eastern nesting area by observing the spatial distribution of other birds – Specifically, the spatial distribution of the Ordinary Snape.</br> <br>The Ordinary Snape has always resided in the Blue Pipits’ Second Nest.</br> <br>When the Blue Pipits from the First Nest migrated south-west to their Second Nest in 2015 where the Ordinary Snape are located, we can see that the number of Ordinary Snape dwindled significantly from 15 in 2014 to 7 in 2015, at a more than 50% decline. Thereafter, possible due to overcrowding, when the population of the Blue Pipits declined from 45 to 27, the population of Ordinary Snape increased from 7 to 18.</br> | **No Migration of other Birds to Dumping Site from 2015 to 2016** ![3 1 - insights](https://user-images.githubusercontent.com/50171205/59183334-56458100-8b9e-11e9-8356-5952ca177ca7.png) ![3 2 - insights](https://user-images.githubusercontent.com/50171205/59183335-56458100-8b9e-11e9-98c5-bf65b28d0ed7.png) **Overcrowding Due to Sudden Influx of Migrated Blue Pipits from 2014 to 2016** ![3 3 - insights](https://user-images.githubusercontent.com/50171205/59183336-56de1780-8b9e-11e9-9436-a61efd8c2120.png) ![3 4 - insights](https://user-images.githubusercontent.com/50171205/59183339-5776ae00-8b9e-11e9-9b36-64b125595fc8.png) ![3 5 - insights](https://user-images.githubusercontent.com/50171205/59183340-580f4480-8b9e-11e9-8a27-55dbe8f0594f.png) |
| <br>**4. Comparison Between Distribution of Rose-crested Blue Pipit and Distribution of Test Rose-crested Blue Pipit from 2011 to 2017**</br> <br>Since the recordings (Test Recordings) provided by Kasios are recently recorded, we want to compare these Test Recordings with the actual recordings obtained most recently in a full year- year 2017.</br> <br>By looking at the location of the test bird recordings provided by Kasios, we can see that it does not commensurate with the historical geo-spatial distribution of Rose-crested Blue Pipits in 2017.</br> <br>Similarly, when we try comparing the spatial distribution of the Blue Pipits for the whole of 2011 to 2017 against the spatial distribution of the Test Recordings, we can see that there several Test Recordings’ locations that deviate away from where we would expect Blue Pipits to be located at, based on the actual recordings locations.</br> | ![4 1 - insights](https://user-images.githubusercontent.com/50171205/59183343-59407180-8b9e-11e9-993b-01167ffd0d7a.png) ![4 2 - insights](https://user-images.githubusercontent.com/50171205/59183344-59d90800-8b9e-11e9-8ec2-2c9673207923.png) |
| <br>**5. Selecting Samples of Actual Recordings for Analysis**</br> <br>Upon plotting the distribution of the Grade A song and call actual recordings, we want to pick samples of actual recordings to be analysed and compared against the Test Recordings. This can be done by visualising where each of the Grade A recordings are located, and to pick those recordings that are located closest to the Test Recordings. Additionally, in order to ensure that we will be able to analyse if the sound waves of the test recordings are similar to the sound waves of the actual recordings, we want to take into account of possible environmental attributes that could lead to a difference in the patterns of recordings in each area. Therefore, we would like to first segregate the recordings into different areas as shown on the right.</br> <br>Since the Test Recordings have no indication of vocalization type – Whether they are song or call vocalization, we will pick the maximum of 25% samples of the population in each coloured zones, or the total population in each coloured zones if the population is less than or equals to 5.</br> <br>Therefore the following indicates the samples of real recordings that we will analyse:</br> <br>**Green Segment (Song)**</br> <br>1. 162563 </br> <br>2. 277952</br> <br>3. 293914</br> <br>4. 377874</br> <br>5. 30397</br> <br>**Green Segment (Call)**</br> <br>1. 181907 </br> <br>2. 111775 </br> <br>3. 293916 </br> <br>4. 368492 </br> <br>5. 298739</br> <br>**Red Segment (Song)** </br> <br>1. 162564 </br> <br>2. 138985 </br> <br>3. 405548</br> <br>**Red Segment (Call)** </br> <br>1. 162567 </br> <br>2. 162569 </br> <br>3. 368493</br> <br>**Purple Segment (Song)** </br> <br>1. 134557 </br> <br>2. 152971</br> <br>**Purple Segment (Call)** </br> <br>1. 405901</br> | ![5 1 - insights](https://user-images.githubusercontent.com/50171205/59183345-59d90800-8b9e-11e9-89e6-556b441af59c.png) |
| <br>**6. Determining Authenticity of Test Recordings: Analysing Patterns Between Test Recordings and Actual Recordings**</br> <br>Upon obtaining the visualisation of both Actual and Test Recordings, we will now be able to examine the authenticity of the Test Recordings.</br> <br> By inspecting the Frequency of all Actual Recordings, we can see that all samples, for both song and call Vocalization Type, tend to deviate between 3kHz to 6kHz. </br> <br> Based on this information, we will attempt to determine the authenticity of the Test Recordings by analysing their wave patterns and to cross reference the analysed patterns against those of the Actual Recordings. </br> <br>***Comparing Actual Green Song and Call With Test Green Recordings***</br> <br>When comparing all Green Songs against the Green Test Recordings, we can see that none of the Green Test Recordings seem to exhibit the same patterns as those of the Actual Recordings. The Test Recordings exhibits an approximate frequency range of 0kHz to 6kHz, 3kHz to 4kHz, 3kHz to 11kHz and 0kHz to 7kHz for Test Green 1, Test Green 6, Test Green 11 and Test Green 15. Test Green 1 and Test Green 6 seem to exhibit periodic vocalization of phrases, whereas Test Green 11 and Test Green 15 tend to produce a sequence of phrases.</br> <br>***Comparing Actual Red Song With Test Red Recordings***</br> <br>Out of all Test Red Recordings, we can see that Test Red 2 and Test Red 9 seem to show similar patterns as Red Song 1: 162564 and to a lesser extent, Red Song 2: 138985, where both exhibited a frequency range between 3kHz to 6kHz, with tandem repeats of what seems like a single phrase-type. Therefore it is possible that these two recordings are authentic.</br> <br>However, the rest of the Test Recordings do not exhibit the same frequency as the Actual Recordings.</br> <br>***Comparing Actual Red Call With Test Red Recordings***</br> <br>In this case, when comparing with Call Recordings, which tend to be periodic vocalization instead of a sequence of notes or phrases, we can see that Test Red 3, Test Red 4 and Test Red 13 could potentially be authentic as well as they do show similar patterns when compared to the Call Recordings.</br> <br>***Comparing Actual Purple Song and Call With Test Purple Recordings***</br> <br>By examining the Test Purple Recordings, it seems that none of the recordings show a similar pattern to our Actual Recordings. Even though Test Purple 8 seems to show a frequency range between 3kHz to 6kHz just as the actual ones do, the sequence of notes displayed is irregular, which is unlike those of the Actual Recordings. Furthermore, the other Test Purple Recordings do not fall within the 3kHz to 6kHz frequency range.</br> | ![6 1 - insights](https://user-images.githubusercontent.com/50171205/59183346-5a719e80-8b9e-11e9-98ae-417f783cfd34.png) ![6 2 - insights](https://user-images.githubusercontent.com/50171205/59183348-5b0a3500-8b9e-11e9-8cfa-dd50d7b29fc3.png) ![6 3 - insights](https://user-images.githubusercontent.com/50171205/59183350-5ba2cb80-8b9e-11e9-9d3a-974c4359cdae.png) ![6 4](https://user-images.githubusercontent.com/50171205/59183351-5ba2cb80-8b9e-11e9-8b44-8d1b04861737.png) ![6 5](https://user-images.githubusercontent.com/50171205/59183353-5c3b6200-8b9e-11e9-8f36-f8f53c253363.png) ![6 6](https://user-images.githubusercontent.com/50171205/59183354-5c3b6200-8b9e-11e9-9b52-5997e1f341de.png) |

## Conclusion

### The following concludes the findings obtained from this analysis:

### Conclusion 1: 
It is highly probable that Kasios’ dumping of process waste had led to the decrease in population of the Rose-Crested Blue Pipits due to the following reasons:


a. Prior to 2015, when Kasios partook in the dumping of process waste, the Rose-Crested Blue Pipits had two distinct habitats based on the location of the Actual Recordings obtained, where one of them is directly located at where Kasios dumped their process waste. From 2015 onwards, we can see a significant shift in location of the Rose-Crested Blue Pipits, where the number of recordings in the dumping site dropped to zero, while the other nesting area to the south-west had a sudden spike in recordings of the Rose-Crested Blue Pipits. This highly suggested that the birds migrated to their second habitat when their first nesting area became uninhabitable due to Kasios’ process waste dump.


b. Two other factors seem to commensurate with the finding above: 
i. Despite the sudden drop in recording of the Rose-Crested Blue Pipits in the dump site, there were no significant increase in the number of recordings of other birds at the site too. This suggests that the area has become totally uninhabitable after the dumping took place. 
ii. The Ordinary Snape resides mainly in the same area as the second habitat of the Rose-Crested Blue Pipits. Right after the suspected influx of the Rose-Crested Blue Pipits in their second nesting area, the total number of recordings of the Ordinary Snape dropped significantly by more than half. This suggests that it is highly possible that due to possible overcrowding and the resultant increase in competition for resources in the area, it has thus led to the drop in the Ordinary Snape’s population size in the area.

### Conclusion 2: 
By analysing the Vocalization type of the Rose-Crested Blue Pipits in the dumping area in 2014, we can see that the vocalization type were all calls and no songs were recorded. Since calls are used to communicate alarms and distress, this could suggest that Kasios had been in the area in 2014, prior to the actual dumping activity in 2015.


### Conclusion 3: 
By comparing the test recordings provided by Kasios against the actual recordings, we were able to analyse the patterns of the sound waves and concluded that only a few samples of the test recordings seem to be authentic. The other test recordings do not exhibit the same patterns or frequency of sound waves as the actual recordings.


a. The test recordings that are most likely to be authentic are:   
i. Test Recording No. 2   
ii. Test Recording No. 9  


b. The test recordings that might be authentic, but to a lesser extent, are:   
i. Test Recording No. 3   
ii. Test Recording No. 4   
iii. Test Recording No. 13  

