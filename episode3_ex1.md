**Exercise 3.1**

1. What roof types are selected by this procedure?
1. How would you restrict this to only one of the roof types?

<details>
  <summary>
Solution
  </summary>
  
1. Do Facet > Text facet on the respondent_roof_type column after filtering. This will show that two names match your filter criteria. They are mabatipitched and mabatisloping.
1. To restrict to only one of these two roof types, you could include more letters in your filter.
</details>

---

**Exercise 3.2**
Use include / exclude to select only entries from one of these two roof types.

<details>
  <summary>
Solution
  </summary>

1. In the facet (left margin), click on one of the names, such as mabatisloping. Notice that when you click on the name, or hover over it, there are entries to the right for edit and include.
1. Click include. This will explicitly include this roof type, and exclude others that are not explicitly included. Notice that the option now changes to exclude.
1. Click include and exclude on the other roof type and notice how the two entries appear and disappear from the table.
</details>

---

**Exercise 3.3**

Sort the data by gps_Altitude. Do you think the first few entries may have incorrect altitudes?.

<details>
  <summary>
Solution
  </summary>

In the gps:Altitude column, select Sort... > numbers and select smallest first. The first few values are all 0. The altitudes are more likely ‘missing’ than incorrect. The survey is delivered by Smartphone with the gps information added automatically by the app. The lack of an altitude value suggests that the smartphone was unable to provide it and it defaulted to 0.
</details>

---

**Exercise 3.4**

We discovered in an earlier lesson that the value for one of the village entries was given as 49. This is clearly wrong. By looking at the GPS coordinates for the entries of the other villages can we decide what village the data in that column was collected from?

1. Sort on gps_Latitude as a number with the smallest first.
1. Add a sort on gps_Longitude as a number with the smallest first.
1. Using the drop down arrow on the village column, select Edit column > Move column to end. This will allow you to compare village names with GPS coordinates.
1. Scroll through the entries until you find village 49. Can you tell from it’s GPS coordinates which village it belong to?
1. Now sort only by interview_date as date. Move the village column to the start of the table. Does the row where village is 49 group with one particular village? Is it the same village as when comparing GPS coordinates?


<details>
  <summary>
Solution
  </summary>

The interview data for that row is in a small cluster of Chirodzo interviews when sorting by GPS coordinates. When sorting by interview date, it is also with Chirodzo interviews. In fact, only Chirodzo had interviews conducted on that date.
  </details>
  
  
  [Episode 4 Exercise 1](episode4_ex1.md)
