# Pnadas_fill_milliseconds_timestap
Create and fill missing timestamps up to 100 millisecond accuracy using pandas and moving average with 5 previous data points in X,Y,Z axis
# first loading the original data from raw JSON which is not in a standard format
# creating the 100 milliseconds timestamp range with the help of numpy and fill all X,Y,Z with NAN values
# Merge the original data and the augmented data so that we can fill the augmented data with the help of real data. as the orignal data has major portion of the timestapms missing
