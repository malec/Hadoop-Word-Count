# Cloud Computing Assignment 1

### Abstract
This basic Java program counts the number of words in file(s), and the number of times the map method is called.

### Implementation
First, to figure out how many times the map method is invoked, I declare a custom key named "A-Map-Counter". An 'A' is put at the start of the string so the result will be at the top of the 1,463 line output file! Then, simply inside the map method of the TokenizerMapper class, I set the mapper context for this key to 1, to indicate one call of the map method. I know that this method is called when a line is mapped because it is set as the job's mapper class.

### Results
After mapping, the keys are reduced, the sum is computed, and the result written to the file "part-r-00000". It should be on the second line. The "A-Map-Counter" value for this job's configuration is 258. Therefore, map is called 258 times.
