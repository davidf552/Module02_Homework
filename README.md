# Module02_Homework
Kestra Homework

# Assignment
So far in the course, we processed data for the year 2019 and 2020. Your task is to extend the existing flows to include data for the year 2021.

## Solution:
Using the Kestra UI seems like the easiest option.

![](https://github.com/davidf552/Module02_Homework/blob/main/q1b.png)

Now it will show here that the year 2021 was uploaded correctly. The same procedure can be made with the yellow taxi.

![](https://github.com/davidf552/Module02_Homework/blob/main/q1.png)

# Note
_Within the execution for Yellow Taxi data for the year 2020 and month 12: what is the uncompressed file size (i.e. the output file yellow_tripdata_2020-12.csv of the extract task)?_


I had to use a [special flow](https://github.com/davidf552/Module02_Homework/blob/main/get_file_size.yaml) with kestra in order to get the answer.



![](https://github.com/davidf552/Module02_Homework/blob/main/q2.png)


If there is another way, I would be grateful to learn how.
