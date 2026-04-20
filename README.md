# QA Case Study – E-Commerce Platform

This repository represents the end-to-end QA strategy, planning, and execution for a demo e-commerce platform.

The project covers multiple testing layers including UI, API, Performance, and Mobile (Responsive) testing.

---

## Objective

To design and implement a comprehensive QA process covering:

- Functional testing
- API validation
- UI automation
- Performance testing
- Mobile responsiveness

---

## Test Scope

The following modules are covered:

- Authentication (Login / Logout)
- Product listing & sorting
- Cart management
- Checkout process
- Booking API (CRUD operations)

---

## Tools & Technologies

| Area 				| Tool 							|
|------				|------							| 
| UI Automation 	| Selenium 						| 
| API Testing 		| Postman + Newman 				|
| Performance 		| JMeter 						|
| Mobile Testing 	| Chrome DevTools (Responsive) 	|
| CI/CD 			| GitHub Actions 				|
| Reporting 		| Allure / HTML Reports 		|

---

## Projects

### Web Automation
https://github.com/gokoguz/web_automation

Covers:
- End-to-end UI scenarios
- Page Object Model structure
- Cross-browser support

---

### API Testing
https://github.com/gokoguz/postman_api_tests

Covers:
- CRUD operations
- Positive & negative scenarios
- Automated execution via Newman

---

### Performance Testing
https://github.com/gokoguz/jmeter-performance-tests

Covers:
- Load, Stress, Spike testing
- Response time & error rate analysis

---

### Mobile Testing (Responsive)
https://github.com/gokoguz/responsive_automation

Covers:
- Different screen resolutions
- Layout validation
- Mobile user experience

Note: Mobile testing was performed using responsive testing approach due to web-based architecture.

---

## Test Coverage Summary

- Functional Testing
- API Testing
- UI Automation
- Performance Testing
- Mobile Testing

---

## Bug Reporting

Bug reports are documented under `/docs/bugs.md`

---

## Documentation

- Test Plan → `/docs/test-plan.md`
- Test Strategy → `/docs/master-test-strategy.md`
- Regression Suite → `/docs/regression-suite.md`

---

## CI/CD

Automated test execution is integrated with GitHub Actions in respective repositories.

---

## Conclusion

This case study demonstrates a structured QA approach including test planning, execution, automation, and reporting across multiple layers of a modern application.