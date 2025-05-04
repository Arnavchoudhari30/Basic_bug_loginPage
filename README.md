🧪 Bug List with Descriptions
BUG_01 - Login with Blank Email Allowed
Description: The system allows the user to click the Login button without entering an email address.
Expected Behavior: It should display an error message like “Email is required.”

BUG_02 - Login with Blank Password Allowed
Description: The login process proceeds even when the password field is left empty.
Expected Behavior: It should show a message such as “Password is required.”

BUG_03 - Invalid Email Format Accepted
Description: Emails in invalid formats (e.g., test@.com, test@domain) are accepted without triggering validation errors.
Expected Behavior: The system should validate the format and display an error: “Enter a valid email address.”

BUG_04 - No Error on Wrong Credentials
Description: Submitting incorrect email/password combinations does not show any error or feedback to the user.
Expected Behavior: It should show an error like “Invalid email or password.”

BUG_05 - Forget Password Link Not Working
Description: The “Forgot Password” link does not redirect the user to the password reset page.
Expected Behavior: Clicking the link should redirect to the password reset screen.
