# C2: Register without @ in #email field

**Template:** Test Case (Text)  
**Type:** Functional  
**Priority:** Medium  

---

## Preconditions
Registration form is opened

## Steps
1. Enter an invalid email ( testgmail.com )
2. Fill in all other fields with valid data
3. Click to register button

## Expected Result
1. Validation message error is displayed near the registration field ( invalid format )
2. All other fields accept data without errors
3. Registration is blocked, user stays on the same page, system highliths the email error
