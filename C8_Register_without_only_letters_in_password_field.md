# C8: Register without only letters in #password field

**Template:** Test Case (Text)  
**Type:** Other  
**Priority:** Medium  

---

## Preconditions
Registration form is displayed

## Steps
1. Enter an invalid password ( 123123 )
2. Fill in all other fields with valid data
3. Click to register button

## Expected Result
1. Validation message error is displayed near the password field ( invalid format )
2. All other fields accept data without an error
3. Registration is blocked, user stays on the same page, system highlights password error
