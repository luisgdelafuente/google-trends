Testing Google Trends

Geo data [/](https://github.com/luisgdelafuente/google-trends/geo_terms.ipynb)


TIME

Current Time Minus Time Pattern:

By Month: 'today #-m' where # is the number of months from that date to pull data for

For example: 'today 3-m' would get data from today to 3months ago
NOTE Google uses UTC date as 'today'
Works for 1, 3, 12 months only!
Daily: 'now #-d' where # is the number of days from that date to pull data for

For example: 'now 7-d' would get data from the last week
Works for 1, 7 days only!
Hourly: 'now #-H' where # is the number of hours from that date to pull data for

For example: 'now 1-H' would get data from the last hour
Works for 1, 4 hours only!

RESOURCES

- Google cagegories & codes   https://github.com/pat310/google-trends-api/wiki/Google-Trends-Categories 
- Pytrends library            https://pypi.org/project/pytrends/
