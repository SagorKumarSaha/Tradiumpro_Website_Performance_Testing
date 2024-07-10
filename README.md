# Tradiumpro Website Performance Testing

### In the "Tradiumpro_PerformaceReport(New_Latest).zip" file, I have done Load Testing on the Tradiumpro website which is a part of Performance Testing.

## Settings that I have applied for load testing-->

1. Number of Threads: 1000 threads will run concurrently.
2. Ramp-up Period: The 1000 threads will start over a period of 10 seconds. This means that JMeter will start 100 threads per second (1000 threads / 10 seconds).
3. Loop Count: Each thread will execute the test scenario 7 times.


## Total Number of Requests:
With 1000 threads and each thread executing the scenario 7 times, the total number of requests will be:
1000 threads * 7 loops = 7000 requests.
