## NP-complete scheduler
This is a job scheduler that answers whether given a set of jobs can be finished in time.

### Parameters
Jobs        : any given jobs can have priority relationship
Processors  : number of processors for handling this problem
Time        : time limit for finishing all the jobs

### Usage 
```
./schedule.py -j [Information of jobs] -p [number of processor] -t [deadline of time]
```

for example
```
./schedule.py -j jobs/kitchen.json -p 1 -t 15
```

