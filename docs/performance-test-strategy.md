# Performance Testing Strategy

## Tools
- Apache JMeter

## Test Types
- Load testing
- Stress testing
- Spike testing
- (Optional) Soak testing

## Scenarios

### Load Test
- 50 users
- 5 minutes
- Expected: avg response < 2s

### Stress Test
- 200 users
- 10 minutes
- System should not crash

### Spike Test
- 0 → 500 → 0 users
- Recovery < 30 seconds

## Metrics
- Avg response time
- 90th percentile
- Throughput (req/sec)
- Error rate (%)

## Pass Criteria
- Error rate < 1%
- No system crash