# AUTH_TC_02_Incorrect_Email

**Author:** Mikhail Prikhodko

**Description:** Verifies login attempt fails with an invalid email.

**Pre-requisite**: The user is registered and has valid credentials, but an incorrect email will be used in this test.

**Test ID:** AUTH_TC_02

**Test Steps:**
| **Step** | **Action** | **Expected Result** |
|----------|------------|---------------------|
| 1        | Navigate to https://demo.prestashop.com/#/en/front. | The "Sign in" button is visible. |
| 2        | Click the "Sign in" button. | The "Email" and "Password" fields are displayed. |
| 3        | Enter "wrongfakemail@mail.com" in the "Email" field. | The input is displayed in the "Email" field. |
| 4        | Enter "Claptrap11" in the "Password" field. | The input is displayed in the "Password" field as masked text. |
| 5        | Click the "Sign in" button. | The error message “Authentication failed.” is displayed. |
   
**Expected Result:** The user does not log in, stays on the login page, and sees an error message indicating incorrect credentials.
