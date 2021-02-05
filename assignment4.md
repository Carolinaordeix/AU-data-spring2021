# Assignment 4

*[Metro Rail Ridership Original data set](https://drive.google.com/file/d/18niW2fD4u9ATF9TPIQWU0NdJtBsi1Fk8/view?usp=sharing)

*[Metro Rail Ridership Clean data set](https://drive.google.com/file/d/1z_EAS0wPn26LC-Dl7VXDpoAmi512ZKPP/view?usp=sharing)

**Cleaning the data - Step by step.**

1. I got rid of column A. ObjectID
2. Deleted column C to N. I just wanted to have data starting 1990.
3. Deleted column AF and AG. I don’t need the coordinates.
4. Understand why there is missing data. It seems related to the fact some stations are new or had open recently. I checked 3 or 4 stations to see when opened. I choose the first four, and after a quick Google search, I confirmed that the opening dates coincide with the information available in the data set.

* Anacostia - Opened Dec 1991
* Branch Ave - Opened Jan 2001
* College Park-U of Md - Opened December 1993
* Columbia Heights - Opened September 1999

5. Colored the cells without information, so I could have an easy way to identify newer stations.
6. I created a new column, “Type of Station,” to sort the stations into three new categories: Original Station, New station, Newer station in the past ten years.
7. Added N/A to the cells with no data.


