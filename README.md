# GWdepthStats
Stats workflow used in research paper. 


This is the Original workflow used to analyse differences between ET, LST and EVI data for deep and shallow WTD classifications

ET,LST, and EVI are subsets from MODIS datasets

WTD data originates from Fan & Miguez Macho dataset for South America. The data were subset into two broad/basic classifications of Depp >10m and Shallow <2m

The data were then compared using wilcoxon rank sum for diffferences in distribution. 
10th and 90th quantiles were also compared using a similar method proposed by Wilcox (2012)  

We randomly selected 1000 deep and 1000 shallow pixels from the classified scene and compared the data from a 12 year period 2001-2012
This random selection and analysis was then replicated 20 times.
