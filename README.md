# UFOs

## Overview
The purpose of this repository is to allow for filtering of the provided UFO data by the user as a part of the web interface. This is accomplished by using JavaScript to dynamically create the HTML table based on the filtering criteria.
## Results
With the updates to the page, results can be filtered on several more criteria. In total the user can filter on Date, City, State, Country, and Shape of the occurrence. The table will filter on the parameters entered into the fields to the left of the table. As many or as few fields can be utilized as you want. The update will occur when the user tabs, enters, or clicks away from a filter field. See below for an example with light events in California on 1/1/2010.

Prior to entering:
![image](https://user-images.githubusercontent.com/40553064/126019796-421313c0-0a1e-435d-8f45-36d0a22a61bb.png)
After entering:
![image](https://user-images.githubusercontent.com/40553064/126019814-dd818f62-4597-484f-b253-27574450f435.png)
Filtering on Date, State, and Shape:
![image](https://user-images.githubusercontent.com/40553064/126019353-40f2b8ee-9653-4599-b33f-768f2c3cead4.png)


## Summary
One current issue with the search functionality is that the city, state, and country fields are all lowercase, and searching with titlecase will yield no results. Another issue is that when ALL filtering criteria are removed, the table does not return to all available lines (See Example snip below).

![image](https://user-images.githubusercontent.com/40553064/126019737-5c4d25f5-385a-408c-b686-4d215fb70ea3.png)

Some potential upgrades would be as follows:
1. Format the input so that capitilization does not impact the results.
2. Allow for searching over a date range rather than a single date.
3. Have a dropdown list where options can be selected, potentially a multi-select field (e.g. light and circle for shape).
