# Adjust_tasks
# TASK 1
Please write a simple CLI application in the language of your choice that does the following: Print the numbers from 1 to 10 in random order to the terminal. Please provide a README, that explains detailed how to run the program on MacOS and Linux.


To work on Mac & Linux:
```bat
cd Task1
sudo chmod +x main.py
./main.py
```

# TASK 2
Imagine a server with the following specs:
4 times Intel(R) Xeon(R) CPU E7-4830 v4 @ 2.00GHz
64GB of ram
2 tb HDD disk space
2 x 10Gbit/s nics
The server is used for SSL offloading and proxies around 25000 requests per second. Please let us know which metrics are interesting to monitor in that specific case and how would you do that? What are the challenges of monitoring this?` 

> Solution
 `Metrics are interesting to monitor`

- [x] Sever running state

- [x] CPU total usage

- [x] CPU usage Breakdown. 

- [x] CPU usage per Core

- [x] CPU temperature

- [x] Memory total usage

- [x] Memory errors

- [x] Network Errors

- [x] Network throughput

- [x] File system

- [x] I/O

- [x] IO read, IO write

- [x] Network traffic

- [x] TCP connection states

- [x] SSL certificate validate status


> We can use promethus + Grafana
 `Attached some screenshoots from grafana`

> Challenges to monitoring this
* Rules and Alerts
* Metrics to monitor
* Metrics should to store to remote storage like S3
* redundancy


