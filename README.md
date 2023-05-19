# pyggykafk
Asynchronously sink Kafka topics into Pandas data frames

## Objective
We wanted a tool aimed at feeding a Pandas dataframe starting from a Kafka
consumer interactively. Right now, we have to this [manually](https://towardsdatascience.com/how-to-read-kafka-clickstream-event-data-in-pandas-96f50e88f7eb), nor there are [real solutions](https://stackoverflow.com/questions/50141544/kafka-to-pandas-dataframe-without-spark) for it.
[This](https://jrott.com/posts/kafka-to-pandas/) is another example for the same use-case.

## Similar projects
There is [this tentative](https://github.com/ikucan/pykafarr/tree/master) storing a single poll retrieved batch
in a Pandas dataframe. We want to actual keep our dataframe up to date with the queried data, cross partition, 
and possibly cross topic.



