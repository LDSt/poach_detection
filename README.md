# Poacher detection using k-means
Given a set of (cartesian) coordinates of animals in a wildlife park tracked over time, detect whether or not a poacher is present nearby at a certain time. 

This approach uses K-Means to cluster animals based on their travelling distance, and then classifies the fastest moving animals as being near a poacher. By coloring only the highest cluster we can clearly see a pattern surrounding the path of the poacher.

This solution could be used to track and stop intruders of wildlife parks before they are able to poach for rhino horn.
