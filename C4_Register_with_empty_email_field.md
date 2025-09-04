# C4: Register with empty #email field

**Template:** Test Case (Text)  
**Type:** Other  
**Priority:** Medium  

---

## Preconditions
Registration form is displayed

## Steps
1. Left email field empty
2. Fill in all other fields with valid data
3. Click to registration button

## Expected Result
1. Validation message error appears near the email field with message ( ... )
2. All other fields accept data without errors
3. Registration is blocked, user stays on the same page, system highlights the email error
