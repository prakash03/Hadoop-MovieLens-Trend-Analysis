# Hadoop-MovieLens-Trend-Analysis
This Repository contains the Mapper and Reducer code for Trend Analysis of Movies using the Movie Lens dataset.

This Project has been executed using Hadoop Streaming and Python on my Local machine with a single Node.

To run this code use the following Hadoop Streaming command below.

$ hadoop jar hadoop-streaming-2.6.0.jar -mapper “mapper.py” -reducer “newreducer.py” -input “movies.csv” -output “output.txt”

The command above saves our results to a text file named 'output.txt' and the results in this can be used for further Analysis.
