# C13: Register with too short <2 #name

**Template:** Test Case (Text)  
**Type:** Functional  
**Priority:** Medium  

---

## Preconditions
Registration form is displayed

## Steps
1. Enter an invalid name ( T )
2. Fill in all other fields with valid data
3. Click to register button

## Expected Result
1. Validation message error is displayed near the name field ( name is too short )
2. All other fields accept data without an error
3. Registration is blocked, user stays on the same page, system highlights password error
