#importance of Encoding Numerical data

--> Whenever we are working on the datasets we have large values like 1212122 so these values doesent give any proper understanding , so in such cases we use the techniques called "Encoding Numerical Data"

**Encoding Numerical data**

 --> Enocding Numerical data is a process of converting Numerical data to Categorical data.

 **Types of Techniques of Encoding Numerical data**

 --> We have to techniques to converts numerical data to categorical data

                          1) Discretization(Binning)

                          2) Binarization
**Discretization**

--> It is the process of transforming the continous variables to discrete variables, by setting a contigous intervals that span the range of variable values.

--> Discretization is also called as Binning.

**Advantages of Discretization**

--> To handle the Outliers

--> To improve the Value Spread, You can spread the middle data.

**Types of Discretization**

--> Discretization is classified int three types 

           1) Unsupervised Binning

           2) Supervised Binning

           3) Custom Binning

**Unsupervised Binning**

--> Unsupervised Binning is used to transform the given input column based on different techniques

--> While Using Unsupervised Binning we have Different categories.

                1) Equal Width(Uniform Binning)

                2) Equal Frequency(Quantiles)

                3) K-Means Binning
                
**Equal Width/Uniform Binning**

--> It is a process of Encoding Numerical data of the input column and dividing equal width of each categories present in the input column

--> The formula that we use to Encode the Input Column

                           formula:-  Max-Min/No of Bins

--> The graphical intution of the data it divides the equal width to each and every histogram.

 **Advantages**

   --> Outliers are handled

   --> Spread Over the data, No change

**Equal Frequency/ Quantile Binning**

--> Every Interval width is not equal in the Equal Frequency 

--> Each Interval Contain 10% of the total Observation

**Advantages of Equal Binning**

--> Outliers are Handling is Efficient.

--> Values spread inform.


**K-Means Binning**

--> In k-means binning we are using clustering algorithm.

--> the algorithm wich we use in k-means binning is k-means

--> the algorithm used to make the clusters,

--> it uses to give the data which are greater than graphical intution of 2D

--> In k-Means binning intervals are also called centroid.

--> So we are creating the intervals randomly

--> After that we are going to draw the Bisect line between two intervals.

--> Here we are going to calculate the every datapoint distance with centroid.

--> After that each and every point distance will compared through clusters and marked as within the particular distance.

--> After that calculating each and every cluster mean and moving the cluster based on the Mean Value.

--> After that repeating the distance from Centrod to data point

--> The process will be continued untill the previous step and current step has no difference.
