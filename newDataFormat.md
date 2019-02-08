For the format, we're just adding the month to the data. As a result, we can just add it to the properties subsection. It makes sense to me to have it go 'Year->Month->Day,' so month will go below year. If we also want to add days, we just add the day below the month.

```
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {
        "Date": "1995",
        "Month": "April",
        "address": "Walnut Street",
        "Count": "3420"
      },
      "geometry": {
        "type": "Point",
        "coordinates": [
          -75.19400775432587,
          39.952714275189656
        ]
      }
    }
  ]
}
```
