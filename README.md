#Automated Analytic Hierarchy Process (AHP) Ranking Calculator Based on Ordinal Features

A PHP implementation of the automated AHP ranking algorithm.

This algorithm ranks data based on ordinal features. For example, a dataset containing marks of two subjects (i.e. features). It functions like normal summing method, but instead of calculating summation of each objects, AHP compares each objects in pairwise in determining the dominancy of the objects in each features. 

#Limitations

This automated AHP only works with ordinal features as pairwise comparison will be done automatically after each features are normalized.

#Usage

The algorithm requires three kind of data:
1. List of criteria (e.g. Coursework marks and Final marks)
2. List of alternatives' id (e.g. Name1, Name2, ...)
3. List of alternatives' features (define in array)

Example of data as the following:
> $criteria =array ("CW","FINAL");

> $alternativeid = array("ID1","ID2","ID3");

> $alternative = array(

> 					array("27.5","23.33","22.5"), //CW

> 					array("8","14","17.5"), //FINAL

> 				);

#License

This library is released under the Universiti Teknikal Malaysia Melaka license. You may use it in personal or commercial projects.
