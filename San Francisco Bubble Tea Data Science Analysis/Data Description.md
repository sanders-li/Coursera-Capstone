## Methodology
To answer the question of which neighborhood in San Francisco is best for a new bubble tea business, one must define what "best neighborhood" indicates.

The following assumptions are made when determining the "best neighborhood".
1. The "best neighborhood" will be defined as a neighborhood with a large population and large number of bubble tea stores. Population and store data will be divided based on each neighborhood's geographical area to best compare neighborhoods of differing sizes.
2. A neighborhood's opulation density is an advantageous to a bubble tea shop as it provides a large quantity of potential customers. A higher population density is preferred regardless of that population's demographics. In other words, we assume there is not a demographic bias in the bubble tea market. 
3. A neighborhood's store density, or stores per square mile, is generally an advantage. While one may think that a lack of competition in a given area is beneficial, the opposite tends to be true. Similar businesses tend to cluster up. For example, major casinos cluster in Las Vegas. Although competition is fierce among businesses, high traffic to the area allows businesses to thrive [2]
4. Eulidean distance is a fair estimate of the distance between two neighborhoods.
5. A service chosen to collect information on the number of existing bubble tea shops has (at least) even coverage. If the data provided is not complete, then each neighborhood in San Francisco is assumed to be equally represented by the service. 

Data will need be collected from multiple sources. As the concept of a "neighborhood" is colloquial, neighborhoods do not possess clear lines of demarcation. In order to determine neighborhoods and process data, it would be useful to have clear geographical lines that divide the neighborhoods. The population and area of each neighborhood should then be determined in order to determine population density. Finally, location data for all stores in San Francisco should be obtained before being classified into neighborhoods and divided by the area. 

For the purpose of determining the best neighborhood, a K-Means algorithm can be used to group similar neighborhoods based on proximity to other neighborhoods, population density, and store density.