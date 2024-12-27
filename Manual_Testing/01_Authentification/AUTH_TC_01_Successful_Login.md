# AUTH_TC_01_Successful_Login

**Author:** Mikhail Prikhodko

**Description:** Verifies successful login with valid credentials.

**Pre-requisite:** The user is registered and has valid credentials.

**Test ID:** AUTH_TC_01

**Test Steps:**
| **Step** | **Action** | **Expected Result** |
|----------|------------|---------------------|
| 1        | Navigate to https://demo.prestashop.com/#/en/front. | The "Sign in" button is visible. |
| 2        | Click the "Sign in" button. | The "Email" and "Password" fields are displayed. |
| 3        | Enter "fakemail@mail.com" in the "Email" field. | The input is displayed in the "Email" field. |
| 4        | Enter "Claptrap11" in the "Password" field. | The input is displayed in the "Password" field as masked text. |
| 5        | Click the "Sign in" button. | The user is redirected to the home page, and the profile icon is visible. |
   
**Expected Result:** The user is successfully logged in and redirected to the home page.
