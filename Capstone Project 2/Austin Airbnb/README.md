Airbnb doesn’t release any data on the listings in its marketplace, a but separate group named Inside Airbnb has extracted data on a sample of the listings for many of the major cities on the website. In this post, we’ll be working with their data set Compiled on March 17th, 2020, on the listings from Austin, TX.

Each row in the data set is a specific listing that’s available for renting on Airbnb in the Austin area. In machine learning terms, each row is an observation. The columns describe different characteristics of each listing (features, in machine learning terms).

To make the data set less cumbersome to work with, we’ve removed many of the columns in the original data set and renamed the file to dc_airbnb.csv.

Here are some of the more important columns (features) we’ll want to work with, because these are all characteristics that a renter might use to assess which listing they will choose:

accommodates: the number of guests the rental can accommodate
bedrooms: number of bedrooms included in the rental
bathrooms: number of bathrooms included in the rental
beds: number of beds included in the rental
price: nightly price for the rental
minimum_nights: minimum number of nights a guest can stay for the rental
maximum_nights: maximum number of nights a guest can stay for the rental
number_of_reviews: number of reviews that previous guests have left
