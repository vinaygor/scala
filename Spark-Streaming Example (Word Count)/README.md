Using Spark shell for this example

Steps:
1. Start a local-server using following command on port 9999: (Window 1)

	nc -lk 9999

   This will open up a connection on port 9999

2. Copy the contents of word_count.scala in the spark-shell (Window 2)

3. Type in the words in the Window 1, and once you hit Enter, spark streaming will reads the words and will produce a word count list of the input

