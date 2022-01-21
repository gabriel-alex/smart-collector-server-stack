# InfluxDB Configuration 

## API routes
Documentation for the API: [InfluxDB API v2](https://docs.influxdata.com/influxdb/v2.0/api/#operation/GetHealth)
``` bash
http://localhost:8086/api/v2/health  #Check the health of your InfluxDB instance
```

## Basic command
``` bash
show databes; # list the database avaiable on influxDB
use [name of the DB]; # select a DB on which operation will be done
show measurements; # display all the table of a DB
Select * from [table name] # display the content of a table
```

## Token

The admin token was generated with [JWT](https://jwt.io/).