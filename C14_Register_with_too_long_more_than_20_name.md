# C14: Register with too long >20 #name

**Template:** Test Case (Text)  
**Type:** Functional  
**Priority:** Medium  

---

## Preconditions
Registration form is displayed

## Steps
1. Enter an invalid name ( Testtesttesttesttestt )
2. Fill in all other fields with valid data
3. Click to register button

## Expected Result
1. Validation message error is displayed near the name field ( invalid format, name is too long )
2. All other fields accept data without an error
3. Registration is blocked, user stays on the same page, system highlights password error
