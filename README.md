# Sensor Analysis
In this case study, I am going to explore sensing data in cars. The goal here is to find insights from this sensing data and possibly develop usecases and value propositions of the importance of having sensors installed in cars, whether for personal use or businesses.

**Dataset Description:** Telematic dataset from United Arab Emirate. The  dataset contains information about 10 cars driving on October 8, 2016. A very important point first. October 8, 2016 is Saturday, which is a weekend in United Arab Emirates (cars coordinates are in this country), so this influences the people activity: some could work, some could entertain themselves, some could buy products for the week and so on.

Also some additional information:
As far as I know speed limit in United Arab Emirates is up to 120 km/h on main roads and 140 km/h on some major express highways(Boy, that's some car racing speed right there). Many drivers maintain higher speed between the speed cameras. So drivers with speeds exceeding the limits should be considered risky.

My analysis goes through the following steps:

- data preparation (dropping unnecessary data and duplicate rows as well as transforming variables);
- looking at basic general information about the cars;
- main analysis of the data and drawing driving pathes of the cars;
- conclusions;
