# Overview 

The purpose of this analysis is to determine whether paid reviews on Amazon influence the ratings. Pyspark is used to create a database on AWS for data analysis. PG Admin is also used in order to create the tables for the database. My analysis looks at pet products available on Amazon. 

# Results 

* I filtered out reviews on products where there are at least 20 votes. Also, we looked at reviews where at least 50 percent of the votes were considered helpful. 
* Of the 38,010 total reviews, 170 were paid reviews. 
* 65 of the paid reviews were 5 star, and 20,612 unpaid reviews were 5 star. 
* 38% of paid reviews had 5 star ratings where 54% of unpaid reviews had a 5 star rating. 

# Summary 

For the pet products on Amazon I think it is hard to conclude that paid reviews yield lower 5 star ratings due to the small sample size. Some reasons the reviews may be lower for paid reviews is because the products that pay for reviews are of lesser quality or aren't as useful. One might conclude that the companies paying for reviews are doing so because they want to boost their ratings. I think a more thorough analysis would include more product types. Pet products only had 170 paid reviews which would leave room for sample bias. 