This repo I try to test my Search api to find nearest car parks by longitude - latitude

### Result:
With : 10 virtual users in 30s
<img width="900" alt="Screenshot 2025-01-08 at 08 47 47" src="https://github.com/user-attachments/assets/f5c53d1a-9a0b-40f4-979b-140eb07500a0" />

#### HTTP Request Duration

- Average: 16.52ms
- 90th Percentile: 20.4ms
- 95th Percentile: 22.78ms

#### Requests per second (RPS): 601.69 requests/s

#### HTTP Failures
- http_req_failed: 0.00% (0 out of 18056)

With : 100 virtual users in 30s

<img width="863" alt="Screenshot 2025-01-08 at 09 53 04" src="https://github.com/user-attachments/assets/61a8320c-bf4f-47fb-8341-0cca2734ce09" />

#### HTTP Request Duration

- Average: 166.03ms
- 90th Percentile: 187.96ms
- 95th Percentile: 252.44ms

#### Requests per second (RPS): 600.746624 requests/s

#### HTTP Failures
- http_req_failed: 0.00% (0 out of 18087)
