# TheMall Performance Testing Using JMeter

This section outlines the results of **load testing** using JMeter, focusing on **concurrent API requests** and the system's **response time**. The test was executed with varying levels of concurrent requests to determine the API's performance and error rate.

## Test Setup

- **Tool Used:** JMeter  
- **Test Type:** Load Testing  

## Test Scenarios

We conducted multiple tests with varying numbers of **concurrent requests** and **loop counts**. Each test scenario was executed with a loop count of **10 iterations**.

### Results for Different Levels of Concurrent Requests:

- **80 Concurrent Requests (10 Loop Count)**  
  - **Avg TPS:** ~16,320  
  - **Total API Requests:** 800  

- **170 Concurrent Requests (10 Loop Count)**  
  - **Avg TPS:** ~34,680  
  - **Total API Requests:** 1,700  

- **200 Concurrent Requests (10 Loop Count)**  
  - **Avg TPS:** ~40,757  
  - **Total API Requests:** 2,000  

- **300 Concurrent Requests (10 Loop Count)**  
  - **Avg TPS:** ~53,341  
  - **Total API Requests:** 3,000  
  - **Error Rate:** **1.6%**  

## Summary

The server can handle approximately **2,500 concurrent API calls** with an **almost zero (0%) error rate**.
