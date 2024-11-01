In this project, I built a machine learning model to predict whether or not a customer would cancel their hotel booking.

I used a dataset on hotel bookings from the article "Hotel booking demand datasets", published in the Elsevier journal, Data in Brief. The abstract of the article stated that the data contained information from two hotels: a resort hotel (H1) and a city hotel (H2). Both datasets shared the same structure, with 31 variables describing 40,060 observations of H1 and 79,330 observations of H2. Each observation represented a hotel booking. Both datasets comprehended bookings that arrived between July 1st, 2015 and August 31st, 2017, including bookings that effectively arrived and bookings that were canceled.

For convenience, I combined the two datasets into a single csv file data/hotel_bookings.csv. I began by importing all the necessary functions needed to import, visualize and model the data.
