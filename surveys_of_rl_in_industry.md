使用场景：有大量数据，需要通过模拟环境进行训练，在真实世界不能有失误



### 方案：

1.  combines the benefits of traditional control theory (e.g. data-efficiency) with the flexibility of RL.  For example, position control is taken care of by a PID controller, and RL contributes the control part that deals with friction and contacts. 



### PAPER:

1. [A Benchmark Environment Motivated by Industrial Control Problems](./relate_papers/A Benchmark Environment Motivated by.pdf) :

   python + java代码，[repo]( https://github.com/siemens/industrialbenchmark )

   python继承了gym构建了自己的环境(industry)，使用openai定义nn。感觉这作为工业的benchmark有点太不行了。

   java代码没仔细看，构建的也是环境