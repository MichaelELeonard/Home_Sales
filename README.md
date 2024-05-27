# Week 22 Challenge – Big data
<img src="ReadMe Pics/Cover Pic 1.png" width="817" height="456">

# Background
In this challenge, we were tasked to use SparkSQL to determine key metrics about home sales data. To accomplish this goal we needed to use Spark to create temporary views, partition the data, and cache and uncache the data.

# Preprocessing
 To start, home_sales_revised.csv was downloaded from an S3 bucket and read into a DataFrame. The datatypes were then viewed to assess if they needed to be updated. 

<br>
<img src="ReadMe Pics/Pic 1.png" width="919" height="452">
<img src="ReadMe Pics/Pic 2.png" width="349" height="225">





<br>
<br>
<br>
<br>
<br>
<br>


<img src="ReadMe Pics/Pic 4.png" width="1025" height="449">
<img src="ReadMe Pics/Pic 3.png" width="372" height="249">
<img src="ReadMe Pics/Pic 5.png" width="215" height="145">
<img src="ReadMe Pics/Pic 6.png" width="214" height="220">
<img src="ReadMe Pics/Pic 7.png" width="218" height="215">
<img src="ReadMe Pics/Pic 8.png" width="272" height="476">
<img src="ReadMe Pics/Pic 9.png" width="286" height="480">
<img src="ReadMe Pics/Pic 10.png" width="285" height="481">
<img src="ReadMe Pics/Pic 11.png" width="366" height="274">
<img src="ReadMe Pics/Cover Pic 2.png" width="843" height="413">
<img src="ReadMe Pics/Cover Pic 3.png" width="731" height="471">
<img src="ReadMe Pics/Cover Pic 4.png" width="827" height="312">



# Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures.  A CSV was received from the Alphabet Soup’s business team, containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Utilize machine learning and neural networks to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
<br>

# Preprocessing
The data was read into a Pandas DataFrame and the EIN and NAME columns were removed.  The variable ‘Is Successful’ was identified to be the ‘target’ of the model with the ‘feature’ variables to include: 
<br>
<br>

* Application Type
* Affiliation
* Classification
* Use Case
* Organization
* Status
* Income Amt
