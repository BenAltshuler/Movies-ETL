# Movies-ETL by Ben Altshuler

## Overview

Amazing Prime sought an automated ETL process to take in dirty data from dispirate sources and, after cleaning, store it in a PostgreSQL database.

## Results

We used Python and and Pandas to read from a movies.csv into DataFrames. We then re-factored our cleaning functions and updated our Postgres tables with one function. 