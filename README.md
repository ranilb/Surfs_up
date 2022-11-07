## Weather Analysis in Huwaii
In this work, weather data from Hawaii was used to determine whether the location is suitable for starting a new business - surf and Shake shop serving surfboards and ice cream. In other words, it is a better idea to check the temperature near the location to see if the temperature is good for the surf lovers and ice cream lovers. This analysis would help to find an investor to start the surf and shake shop.

### Resources
Data base: huwaii.sqlite                                                                                                                      
Software: Jupyter notebook, SQLite, SQLAlchemy, and Flask

## Results of the weather analysis
In this analysis, we mainly focus on the temperature in the summer (June) and the temperature in the winter (December). The temperature data was obtained from the huwaii.sqlite file in the range of 2010 to 2017. 

### The Month of June
* The temperature data of the first 10 days in Jume is presented below and it can be observed that the temparature is good for surfing and selling ice cream. 
    
    ![Screen Shot 2022-11-06 at 10 24 23 PM](https://user-images.githubusercontent.com/112113327/200220297-971b823d-a7be-4b8b-8d35-04570c7e23db.png)

* Considering the entire data set for the month of June for about 1700 observarions, the mean, medean, maximum temperature, quartiles and the standerd deviations were computed. The following image shows the temperature statistics for the month of June.

    ![Screen Shot 2022-11-06 at 9 39 39 PM](https://user-images.githubusercontent.com/112113327/200220805-930d288a-7fd5-42b0-bd48-52127c775891.png)
    
* The graph of June temperature data is given below. It can be oberved that temperature is very consistent during the time period.
    
    ![Screen Shot 2022-11-06 at 10 41 43 PM](https://user-images.githubusercontent.com/112113327/200222026-142d9105-0405-4a0f-a5e7-536874657256.png)


### The Month of December
* The temperature data of the first 10 days in December is shown below. It can be observed that the temparature is suitable for surfing and selling ice cream. 
    
   ![Screen Shot 2022-11-06 at 10 24 42 PM](https://user-images.githubusercontent.com/112113327/200222405-8db8fe23-5281-42e6-b91b-207816dc5cd9.png)


* Next, the entire data set for the month of December was considered. From those 1517 observarions, the mean, medean, maximum temperature, quartiles and the standerd deviations were computed. The following image shows the temperature statistics for the month of December.

   ![Screen Shot 2022-11-06 at 9 39 55 PM](https://user-images.githubusercontent.com/112113327/200222698-2677214c-bbbc-4eb0-8ded-89d57d002102.png)
   
    
* The graph of December temperature data is given below. It can be oberved that there are reasonable number of dates with the temperature is below 70 degrees.
    
   ![Screen Shot 2022-11-06 at 10 50 22 PM](https://user-images.githubusercontent.com/112113327/200222850-c63f7003-c8ea-4bad-9fc0-ac9e67e6f38e.png)

