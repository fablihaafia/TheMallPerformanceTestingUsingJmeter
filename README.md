# TheMallPerformanceTestingUsingJmeter

This section outlines the results of load testing using JMeter, focusing on concurrent API requests and the system's response time. The test was executed with varying levels of concurrent requests to determine the API's performance and error rate.

Test Setup:
Tool Used: JMeter
Test Type: Load Testing

Test Scenarios:
We conducted multiple tests with varying numbers of concurrent requests and loop counts. Each test scenario was executed with a loop count of 10 iterations. Below are the results for different levels of concurrent requests:

Concurrent Requests	Total API Requests	Avg TPS (Total Samples)	Error Rate	Notes
80 Concurrent Request with  10 Loop Count; Avg TPS for Total Samples is ~ 16,320 And Total Concurrent API requested: 800.
170 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 34680 And Total Concurrent API requested: 1700.
200 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 40757 And Total Concurrent API requested: 2000.
300 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 53341 And Total Concurrent API requested: 3000.

While executed 300 concurrent request, error rate is 1.6%. 

Summary: Server can handle almost concurrent 2500 API call with almost zero (0) error rate.
