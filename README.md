# hashcode_2021
## Google Hash Code 2021
The description of the problem can be found in this file: [hashcode_2021_online_qualifications.pdf](https://github.com/dejvidB/hashcode_2021/blob/main/hashcode_2021_online_qualifications.pdf)

### `codit-21` Team Members
- [Dejvid Bushi](https://github.com/dejvidB)
- [Theodoros Fragkoulis](https://github.com/theofrag)
- [Giannis Zapantis](https://github.com/tech-gian)

### Input/Output files
In the folder named [`input files`](https://github.com/dejvidB/hashcode_2021/tree/main/input%20files) you can find the input data provided by Google.  
Given those files, after certain calculations our program prints the results in the desired format. Those results can be found in the folder named [`output files`](https://github.com/dejvidB/hashcode_2021/tree/main/output%20files).  
Each .txt file in input files has a corresponding .txt file in output files.

### Program source code and compilation
The code for our solution can be found in [`final.cc`](https://github.com/dejvidB/hashcode_2021/blob/main/final.cc). It can be compiled by g++ compiler using the command `g++ final.cc -o final`.  
Then you can run the executable file providing an input file and a destination file for the output. For example, the command for executing the program with `a.txt` as input file (and exporting results in `a_results.txt`) would be `./final < ./input\ files/a.txt > ./output\ files/a_result.txt`.

### Algorithm description
Streets are sorted based on points which are equal to the amount of cars they are intially going to have in descending order. Then, they are divided into three caterories by taking into consideration their amount of points and comparing them with naively chosen numbers. This way, streets with the most cars have a green traffic light on for 3 seconds. Streets with the fewest cars have their green traffic light on for only 1 second, while streets with an average amount of cars get 2 seconds. 

We managed to score 8,148,907 points and rank position 3683 globally!
