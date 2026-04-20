# Bug Report

## BUG-001

* **Title:** Login error message is not displayed correctly
* **Environment:** Chrome (latest), Windows 11
* **Severity:** Medium
* **Priority:** P2

### Steps

1. Go to login page
2. Enter invalid password
3. Click Login

### Expected

Error message should be displayed under the password field

### Actual

Error message appears at top of the page

---

## BUG-002

* **Title:** API returns 200 OK for invalid credentials
* **Environment:** API - /auth endpoint
* **Severity:** High
* **Priority:** P1

### Steps

1. Send POST request to /auth with wrong password

### Expected

401 Unauthorized OR proper error handling

### Actual

200 OK returned with error message

---

## BUG-003

* **Title:** Booking endpoint returns 500 instead of validation error
* **Environment:** API - /booking
* **Severity:** High
* **Priority:** P1

### Steps

1. Send POST /booking with missing required fields

### Expected

400 Bad Request with validation message

### Actual

500 Internal Server Error

---

## BUG-004

* **Title:** Response time exceeds threshold in auth endpoint
* **Environment:** Performance Test
* **Severity:** Medium
* **Priority:** P2

### Steps

1. Run auth request under load

### Expected

Response time < 500 ms

### Actual

Response time ~4500 ms

---

## BUG-005

* **Title:** UI layout breaks on small screen (375px)
* **Environment:** Mobile responsive (Chrome DevTools)
* **Severity:** Medium
* **Priority:** P2

### Steps

1. Open site in 375px width
2. Navigate to product page

### Expected

Elements should be responsive and aligned

### Actual

Buttons overlap and layout breaks