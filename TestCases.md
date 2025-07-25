# 🧪 Manual Test Cases – E-Bus Management System

**Project Name:** E-Bus Management Based on Current Location System  
**Version:** 1.0  
**Tested By:** Charan  
**Test Date:** 2025-07-25  
**Testing Type:** Functional, UI, Usability, and Security Testing  
**Test Result Summary:** ✅ 100% Test Cases Passed. No bugs or defects remain.

---

## ✅ Test Cases

| Test ID | Module      | Test Scenario                  | Test Steps                                                                 | Expected Result                               | Status |
|--------|-------------|--------------------------------|----------------------------------------------------------------------------|-----------------------------------------------|--------|
| TC001  | Login        | Valid Login                    | Enter valid email & password and click login                              | Redirects to dashboard                         | ✅ Pass |
| TC002  | Login        | Invalid Login                  | Enter wrong password                                                      | Shows error message                           | ✅ Pass |
| TC003  | Register     | New user registration          | Enter email & password and click register                                 | Creates account and redirects to login         | ✅ Pass |
| TC004  | Search Bus   | Valid route search             | Enter source "Suryapet" and destination "Hyderabad"                       | Displays matching buses                        | ✅ Pass |
| TC005  | Search Bus   | Without login                  | Try accessing search page without login                                   | Redirects to login page                        | ✅ Pass |
| TC006  | Add Bus      | Add bus details (Driver role)  | Login as driver and fill bus form with all valid details                  | Adds bus and makes it available in search      | ✅ Pass |
| TC007  | Add Bus      | Incomplete form submission     | Leave required fields empty                                               | Shows validation error                         | ✅ Pass |
| TC008  | Security     | Unauthorized access to admin   | Open admin dashboard URL without login                                    | Shows access denied or redirects to login      | ✅ Pass |
| TC009  | UI           | Mobile responsiveness          | Open app on a mobile browser                                              | Layout is responsive and adapts to screen      | ✅ Pass |
| TC010  | Navigation   | Navbar link navigation         | Click all links in the navigation bar                                     | Redirects to corresponding pages smoothly      | ✅ Pass |

---

## Final Remarks:
All test cases have passed successfully. The E-Bus Management System meets the defined functional and non-functional requirements. No bugs or defects are pending. The application is ready for deployment and production use.