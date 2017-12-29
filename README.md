# redshift

This repository contains a simple forecast engine for the data provided. The following approach was taken:
1. Format data using Pandas.
2. Determine points of observation by trying to minimize the RMSE between different points. (This will provide the period of observation of our data).
3. Evaluate our model, to determine how it works.
4. Predict for future data (case for Data A)

Note: This will be the simplest solution, if the amout of time is restricted. If more time is available, a better solution can be developed by doing some research.
