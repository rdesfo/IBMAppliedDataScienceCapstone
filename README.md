# IBMAppliedDataScienceCapstone
The repository contains the files of my [IBM's Applied Data Science Capstone Project][capstone].

## Additional Notes

### Booster Version Category Count (slide 31)

The Dashboard assignment generates charts of the different categories outcomes.
However, I feel a table more clearly presents the data since it doesn't require
counting different colored dots find the results.

```python
>>> spacex_df.groupby(['Booster Version Category','class'])['class'].size()
Booster Version Category  class
B4                        0         5
                          1         6
B5                        1         1
FT                        0         8
                          1        16
v1.0                      0         5
v1.1                      0        14
                          1         1
```

### Folium Images

It appears that folium interactive maps don't get saved as images.  This requires the notebook to
be run to view the maps.  This can be accomplished by downloading and running manually or by using
[nbviewer][nbviewer]


[capstone]: https://www.coursera.org/learn/applied-data-science-capstone
[nbviewer]: https://nbviewer.org/github/rdesfo/IBMAppliedDataScienceCapstone/blob/main/lab_jupyter_launch_site_location.ipynb
