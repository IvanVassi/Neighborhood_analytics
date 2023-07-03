# Neighborhood_analytics
Geospatial analysis between different amenities in Almaty (Kazakhstan)

We conducted this analysis as an exercise to explore the application of geo-analytics tools and association rules mining from geo-data, followed by their interpretation.

The association between pharmacies and schools is the strongest, with a support of 0.481. This indicates that in 48.1% of cases, pharmacies are located near schools. The confidence value of 0.741 suggests that if a pharmacy is present, there is a 74.1% chance of a school being nearby. The lift value of 1.217 indicates a slightly positive correlation between pharmacies and schools.

In order to enhance clarity, we will represent pharmacies with red dots and schools with yellow dots on the map.

Similarly, when considering schools as the antecedent and pharmacies as the consequent, we find a similar support value of 0.481. The confidence value of 0.790 indicates that if a school is present, there is a 79.0% chance of a nearby pharmacy. The lift value of 1.217 suggests a slightly positive correlation between schools and pharmacies.

The association between fuel and pharmacies has a support value of 0.320, indicating that in 32% of cases, pharmacies are located near fuel stations. The confidence value of 0.641 suggests that if a fuel station is present, there is a 64.1% chance of a nearby pharmacy. However, the negative leverage and conviction values indicate that the presence of fuel stations does not strongly influence the occurrence of pharmacies.

Conversely, when considering pharmacies as the antecedent and fuel as the consequent, we find a similar support value of 0.320. The confidence value of 0.493 indicates that if a pharmacy is present, there is a 49.3% chance of a nearby fuel station. Similar to the previous association, the negative leverage and conviction values suggest that the presence of pharmacies does not strongly influence the occurrence of fuel stations.

The association between pharmacies and hospitals has a support value of 0.289, indicating that in 28.9% of cases, pharmacies are located near hospitals. The confidence value of 0.445 suggests that if a pharmacy is present, there is a 44.5% chance of a nearby hospital. The lift value of 1.258 indicates a slightly positive correlation between pharmacies and hospitals.
