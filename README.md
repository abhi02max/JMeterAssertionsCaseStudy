# JMeter Assertions Case Study

Focused Apache JMeter examples for validating HTTP responses during performance-test execution.

## Test plans

- Response assertion
- JSON assertion
- XPath assertion
- Duration assertion
- Response-size assertion

## Run

```bash
jmeter -n -t Response-Assertions.jmx -l results.jtl
```

Review the plan in the JMeter GUI before pointing it at any non-local environment. Load tests should only target systems you are authorised to test.
