## EDA using pandas and Data analysis using Excel

![image](https://user-images.githubusercontent.com/61554733/202708583-ff27dbc0-dfff-4841-86b0-a47bf32bc75a.png)


### EDA using pandas 
Following were the steps that i followed to make data clean and structured to analyse it.

1.Understanding the data
2.Clean the data(Remove blank values ,NAN values etc)
3.Calculate and append the coloumns for making the analysis of data easier
4.Visuallizing the data for potential outlier values

My goals for the given data- 

1.Analyse the visualised form of cleaned to get insights for the same.
2.Calculating the value of sales for each Cust id
3.Visualising top customers of our firm
4.Top products by value


<img width="982" alt="image" src="https://user-images.githubusercontent.com/61554733/202708405-059610fc-91c8-4da6-8dbb-6b79d7976752.png">


So lets move towards the insights that i infered from the given data

Visualising the given data

<img width="456" alt="image" src="https://user-images.githubusercontent.com/61554733/202714048-c716d740-b98f-42ee-85ed-b004b35bdfd2.png">

(X-axis represents the Value(ie. Quantity multiplied by cost)(Y-axis represents Cust ids of given customers)
We can infer from this graph that most of our customers are concentrated in a range of value less than 5000 with some exceptions being also present

We can also spot some of the outliers in the data as well


<img width="1128" alt="image" src="https://user-images.githubusercontent.com/61554733/202716789-57fd99b6-3813-460c-b144-4079222c149a.png">

(X-axis represents the Cust ids)(Y-axis represents value of sales for each given customers)
In the above graph we can see that there is a disproportinate distribution of sales value this can be also be with the standard deviation of the given data

Here standared deviation is 18896.23 for the mean 7960.7 
By calculating the std and mean we can understand that our intial perception of data being mostly concentrated is not entierly correct though it is some what concentrated.

#### Further insights from the dataset- 
#### 1. The total customers are 4372 are visiting the website
#### 2. Avg value of sales is 1920 per customer 
#### 3. Only 20.9% customers are ordering greater than the average value of Sales 
#### 4. An approxiamte of 93 vists per customer can be concluded from the data




