# Load Pattern Clustering

## Overview

This notebook applies clustering algorithms to residential electricity consumption profiles from the London Smart Meters dataset, with the goal of identifying common behavioral patterns among end users.
Dataset

    Source: Kaggle - London Smart Meters
    Period: 2011-2014 (2013 is the only year that has been considered)
    Users: ~5,500 residential customers
    Granularity: Half-hourly consumption data

## Scope of this work

This project aims to find similar characteristics between different clients and grouping them into coherent clusters, using the k-means clustering algorithm. The clustering results will then be compared to the existing ACORN classification of each client to verify if the different classification successfully translate to a different load consumption.
