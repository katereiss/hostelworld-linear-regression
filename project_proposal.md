### **Question/need:**

What features best predict hostel prices? Atmosphere, security, location, and overall rating are examples of features that influence travelers’ experiences and that may influence price as well. Budget travelers and hostel owners would be interested in predicting hostel prices. In this project, I create a model that predicts hostel prices in South America based on [Hostelworld.com](http://Hostelworld.com) data. 

### **Data Description:**

Hostelworld provides data on hostels in South America. I will scrape the website for hostel name, price for a dorm bed in USD, location in relation to city center, city name, overall rating out of 10, number of reviews, features such as free wifi and breakfast, and rating out of 10 in the following areas: Value For Money, Security, Location, Staff, Atmosphere, Cleanliness, Facilities. Each row in my table will be one hostel, and the final product will have about 2,000 hostels in South America. Hostel price will be the target of my model.

### **Tools:**

I will scrape [Hostelworld.com](http://Hostelworld.com) using BeautifulSoup in order to acquire the data. Scikit-learn will be used to determine linear regression models. 

### **MVP Goal:**

The MVP will be a linear regression model that predicts hostel prices for hostels in Medellin, Colombia. I will start with this set of about 45 hostels since it is scalable and will provide insights on a small data set. From there, I will scale my model to about 400 hostels in the country, then to about 2,000 in the continent. I will select and evaluate the model extensively for the final product.
