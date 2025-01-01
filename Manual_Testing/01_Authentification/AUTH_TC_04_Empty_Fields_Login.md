# AUTH_TC_04_Empty_Fields_Login

**Author:** Mikhail Prikhodko  

**Description:** Verifies login attempt fails when both "Email" and "Password" fields are empty.  

**Pre-requisite:** No specific prerequisites.  

**Test ID:** AUTH_TC_04  

**Test Steps:**  
| **Step** | **Action** | **Expected Result** |  
|----------|------------|---------------------|  
| 1        | Navigate to https://demo.prestashop.com/#/en/front. | The "Sign in" button is visible. |  
| 2        | Click the "Sign in" button. | The "Email" and "Password" fields are displayed. |  
| 3        | Leave the "Email" and "Password" fields empty. | The fields remain empty. |  
| 4        | Click the "Sign in" button. | An error message "Authentication failed." or a specific message for empty fields is displayed. |  

**Expected Result:** The user does not log in, stays on the login page, and sees an appropriate error message indicating that fields cannot be empty.