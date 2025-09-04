# C15: Register with empty field #name

**Template:** Test Case (Text)  
**Type:** Functional  
**Priority:** Medium  

---

## Preconditions
Registration form is displayed

## Steps
1. Leave the name field empty
2. Fill in all other fields with valid data
3. Click to register button

## Expected Result
1. Validation message error is displayed near the password field ( invalid format, name field is required )
2. All other fields accept data without an error
3. Registration is blocked, user stays on the same page, system highlights password error
