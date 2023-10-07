# Case_Studies
This repository hosts sample projects that demonstrate various real-world scenarios using different datasets.

### 1. Aerofit - Descriptive Statistics & Probability
##### Data Set Information:
The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.
Perform descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts.
For each AeroFit treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business
#### Attribute Information:
- Product Purchased : KP281, KP481, or KP781
- Age : _In years_
- Gender : _Male/Female_
- Education : _In years_
- MaritalStatus : _Single or Partnered_
- Usage : _The average number of times the customer plans to use the treadmill each week_
- Income : _Annual income (in dollars)_
- Fitness : _Self-rated fitness on a 1 to 5 scale, where 1 is the poor shape and 5 is the excellent shape_
- Miles : _The average number of miles the customer expects to walk/run each week_

### 2. Delhivery - Feature Engineering
##### Data Set Information:
Delhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities. The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.
The company wants to understand and process the data coming out of data engineering pipelines. Clean, sanitize and manipulate data to get useful features out of raw fields. Make sense out of the raw data and help the data science team to build forecasting models on it.
#### Attribute Information:
- data - _whether the data is testing or training data_
- trip_creation_time – _timestamp of trip creation_
- route_schedule_uuid – _unique Id for a particular route schedule_
- route_type – _Transportation type_
- FTL – _Full Truck Load: FTL shipments get to the destination sooner, as the truck is making no other pickups or drop-offs along the way_
- Carting - _handling system consisting of small vehicles (carts)_
- trip_uuid - _unique ID given to a particular trip (A trip may include different source and destination centers)_
- source_center - _source ID of trip origin_
- source_name - _source Name of trip origin_
- destination_cente – _destination ID_
- destination_name – _destination Name_
- od_start_time – _trip start time_
- od_end_time – _trip end time_
- start_scan_to_end_scan – _time taken to deliver from source to destination_
- actual_distance_to_destination – _distance in Kms between source and destination warehouse_
- actual_time – _actual time taken to complete the delivery (cumulative)_
- osrm_time – _an open-source routing engine time calculator which computes the shortest path between points in a given map
(includes usual traffic, distance through major and minor roads) and gives the time (cumulative)_
- osrm_distance – _an open-source routing engine which computes the shortest path between points in a given map
(includes usual traffic, distance through major and minor roads) (cumulative)_
- segment_actual_time – _this is a segment time. Time taken by the subset of the package delivery_
- segment_osrm_time – _this is the OSRM segment time. Time taken by the subset of the package delivery_
- segment_osrm_distance – _this is the OSRM distance. Distance covered by subset of the package delivery_

### 3. Netflix - Data Exploration and Visualisation
##### Data Set Information:
Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as cast, directors, ratings, release year, duration, etc.
Analyze the data and generate insights that could help Netflix team deciding which type of shows/movies to produce and how they can grow the business in different countries.
#### Attribute Information:
- Show_id: _Unique ID for every Movie / TV Show_
- Type: _Identifier - A Movie or TV Show_
- Title: _Title of the Movie / TV Show_
- Director: _Director of the Movie / TV Show_
- Cast: _Actors involved in the Movie / TV Show_
- Country: _Country where the Movie / TV Show was produced_
- Date_added: _Date Movie / TV Show was added on Netflix_
- Release_year: _Actual Release year of the Movie / TV Show_
- Rating: _TV Rating of the Movie / TV Show_
- Duration: _Total Duration - in minutes or number of seasons_
- Listed_in: _Genre_
- Description: _The summary description_

### 4. Parkinsons Disease Detection Using Ensemble Methods
The data consists of those diagnosed with Parkinson's Disease and those who do not.
#### Source:
The dataset was created by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, which recorded the speech signals. The original study published the feature extraction methods for general voice disorders.
##### Data Set Information:
This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds to one of 195 voice recordings from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for PD.
#### Attribute Information:
- name - _ASCII subject name and recording number_
- MDVP:Fo(Hz) - _Average vocal fundamental frequency_
- MDVP:Fhi(Hz) - _Maximum vocal fundamental frequency_
- MDVP:Flo(Hz) - _Minimum vocal fundamental frequency_
- MDVP: Jitter(%), MDVP: Jitter(Abs), MDVP: RAP, MDVP: PPQ, Jitter: DDP - _Several measures of variation in fundamental frequency_
- MDVP:Shimmer, MDVP: Shimmer(dB), Shimmer: APQ3, Shimmer: APQ5, MDVP: APQ, Shimmer: DDA - _Several measures of variation in amplitude_
- NHR, HNR - _Two measures of the ratio of noise to tonal components in the voice_
- RPDE, D2 - _Two nonlinear dynamical complexity measures_
- DFA - _Signal fractal scaling exponent_
- spread1, spread2, PPE - _Three nonlinear measures of fundamental frequency variation_
- Status - _Health status of the subject (one) - Parkinson's, (zero) - healthy_

### 5. Walmart - Confidence Interval and Central Limit Theorem
##### Data Set Information:
The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men?
#### Attribute Information:
- User_ID : _User ID_
- Product_ID : _Product ID_
- Gender : _Sex of User_
- Age : _Age in bins_
- Occupation : _Occupation (Masked)_
- City_Category : _Category of the City (A,B,C)_
- Stay_In_Current_City_Years : _Number of years stay in current city_
- Marital_Status : _Marital Status_
- Product_Category : _Product Category (Masked)_
- Purchase : _Purchase Amount_

### 6. Yulu - Hypothesis Testing
##### Data Set Information:
Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting. Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!
#### Attribute Information:
- datetime: _datetime_
- season: _season (1: spring, 2: summer, 3: fall, 4: winter)_
- holiday: _whether day is a holiday or not_
- workingday: _if day is neither weekend nor holiday is 1, otherwise is 0_
- weather:
  1: __Clear, Few clouds, partly cloudy, partly cloudy_
  2: _Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist_
  3: _Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds_
  4: _Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog_
- temp: _temperature in Celsius_
- atemp: _feeling temperature in Celsius_
- humidity: _humidity_
- windspeed: _wind speed_
- casual: _count of casual users_
- registered: _count of registered users_
- count: _count of total rental bikes including both casual and registered_
