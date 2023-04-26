# Convert Crons to Human Readable strings

cron-descriptor python library: https://pypi.org/project/cron-descriptor/


## Goal: Create a Snowpark UDF that converts chron spec to human readable string that can be called in Sigma

_____________


#### Precursor Steps:

1. Follow along with the quickstarts: https://quickstarts.sigmacomputing.com/guide/snowflake_snowpark_udf_python/index.html?index=..%2F..index#0
2. Most importantly, pay attention to the virtual environment section.
3. ```pip install cron-descriptor```
4. In Sigma, reference the UDF by entering into the formula bar ```CallVariant("MY_DATABASE.MY_SCHEMA.CRON_DESCRIPTOR_UDF", [Cron Spec])```

_____________

![Screenshot 2023-04-26 at 1 48 36 PM](https://user-images.githubusercontent.com/120054623/234698986-fd4947b5-9538-4577-9b97-5b7df3e29119.png)

