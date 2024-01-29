# ScholarshipJmeterReport

- This is the full test report of scholarship platform generated by Jmeter.
- Please visit [ScholarshipJmeterReport] (https://davewylee.github.io/ScholarshipJmeterReport/) for full report.
- Please visit [ScholarshipScholarship1219] (https://github.com/LyndonYeh/Scholarship1219) for the project tested.

## TestData
### API calls
Number of new scholarships: 3000
Number of logins: 40

### test script
Execution threads: 10
Startup delay: 5 seconds
Loop duration: 20 minutes

### Test script process
Log in 10 users within 5 seconds
100 requests per user
Repeat 3 times

### Summary report
Total number of requests (#Samples): 3040 times
Average response time (Average): 3918(ms)
Minimum response time (Min): 1(ms)
Maximum response time (Max): 48363(ms)
50% user response time (Median): 3940.00(ms)
Standard offset/standard deviation (Std.Dev): 986.29
Error rate (Error %): 0.92%
Request throughput per second (Throughtput): 2.52/sec
Received KB/sec: 3772.19
Send KB/sec: 0.61
