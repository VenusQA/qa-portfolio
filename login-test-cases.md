# Login Test Cases

| Test Case ID | Scenario | Steps to Reproduce | Expected Result | Status |
|--------------|----------|--------------------|----------------|--------|
| TC-001       | Valid login | 1. Go to login page <br> 2. Enter valid username/password <br> 3. Click Login | User is redirected to dashboard | Pass |
| TC-002       | Invalid password | 1. Go to login page <br> 2. Enter valid username + wrong password <br> 3. Click Login | Error message: "Invalid credentials" | Pass |
| TC-003       | Empty fields | 1. Go to login page <br> 2. Leave fields blank <br> 3. Click Login | Error message: "Fields required" | Pass |
