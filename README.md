# Kleindl-Et-Al.-Ecological-Applications
 Ecological Applications:  Integrating Variance into Ecological Assessment: A Practical Application of Modern Portfolio Theory  -  Author Names: Kleindl, W.J., P.C. Stoy, F. Kerins, M.C. Rains   Contact; william.kleindl@montana.edu 

Ok, here is the truth. My R skills are a lot like my carpentry skills. I can make a chair, and you can sit in it, but it will not be beautiful! There is likely more brute-force coding that you would like to see. But it does the job. 
!!Warning: Some libraries may be deprecated!! 

Below is a simple table of contents for the code: 
1.	Section 1 Library and WD
2.	Section 2 GEE code 
    a.	in JAVA and commented here
3.	Section 3 Random Forest training and classification
    a.	 These classification algorithms were established for 2005 and 2013 training data
4.	Section 4 Classifying all years.
    a.	I applied that to all years once the classification method was set. Then I cleaned up the maps by clipping them to areas of interest and classifying them by known class covers (river, road, etc.) and smooth salt and pepper. 
5.	Section 5 Remote Sensing Analysis
    a.	In this section, I apply metric scores for each pixel. These metrics are: Fragmentation, Patch Diversity, Land Use. They are applied to the floodplain and buffer by reach. Those reaches were defined in ESRI GIS by the methods described in the paper. The scores were also applied at different scales.
6.	Section 6 Application of Portfolio Analysis
    a.	At this point, all classification is complete and are stored in RS Image/The Final Maps. The following code sets up the base data to analyze the metrics. This requires the percent cover of each class and the count of pixels per class. These are done for both the floodplain and buffer.
7.	Section 7 Bootstrap across scale 
    a.	Here, we looked at the change in portfolio volatility as we increased sample grain.
8.	Section 8 Cumulative Volatility. 
    a.	Here, we increase the sample size to see the effect on portfolio volatility.
9.	Section 9 Final Figures
    a.	Several final figures were made here, but others were cleaned in Illustrator.
