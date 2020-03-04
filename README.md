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
The server is used for SSL offloading and proxies around 25000 requests per second. Please let us know which metrics are interesting to monitor in that specific case and how would you do that? What are the challenges of monitoring this?

Solution
Metrics are interesting to monitor

* Sever running state

* CPU total usage

* CPU usage Breakdown. 

* CPU usage per Core

* CPU temperature

* Memory total usage

* Memory errors

* Network Errors

* Network throughput

* File system

* I/O

* IO read, IO write

* Network traffic

* TCP connection states

* SSL certificate validate status


We can use promethus + Grafana
Attached some screenshoots from grafana

Challenges to monitoring this
Rules and Alerts
Metrics to monitor
Metrics should to store to remote storage like S3
redundancy


