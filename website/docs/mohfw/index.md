# Ministry of Health & Family Welfare

URL:  [Ministry of Health & Family Welfare](https://www.mohfw.gov.in/)

Publishes the latest state level cases data. We have archived the data so we can get time series. More details are on [this blog](https://thejeshgn.com/2020/03/16/novel-corona-virus-covid19-archive-api-india-data/).


Before using this data, please note the following:
 
 1. Data is published by Ministry of Health & Family Welfare
 2. We only arhive, scrape and parse the data.


## DataMeet Discussions 
You can follow and participate in discussions at [DataMeet](https://groups.google.com/forum/#!topic/datameet/_HnOB5iyEx0)

## HTML Archive

We backup the HTMLs as and when it gets published. You can find them inside [mohfw-backup](https://github.com/datameet/covid19/tree/master/mohfw-backup) folder.

## Parsed Data

Parsed data in the form of JSON is availabe inside [data](https://github.com/datameet/covid19/tree/master/mohfw-backup). We update once a day. It has historical data since 2020-03-12T11:00:00.00+05:30

There is one record for each state and report_time combination.

```
{   "id":"2020-03-12T11:00:00.00+05:30|dl",
   "key":"2020-03-12T11:00:00.00+05:30|dl",
   "value":{
      "_id":"2020-03-12T11:00:00.00+05:30|dl",
      "_rev":"1-1b430a0a4b4a8b43fdab12d040ae8735",
      "state":"dl",
      "report_time":"2020-03-12T11:00:00.00+05:30",
      "confirmed_india":6,
      "confirmed_foreign":0,
      "cured":0,
      "death":0
	}
}
```

## API

Send an email to thej@datameet.org to get access to API.


## Usage
1. [COVID19 Cases In India - Graph](https://thejeshgn.com/projects/covid19-india/)

## Credit
Please credit DataMeet if you use this data.
