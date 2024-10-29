Knowledge:
- All dragged elements to form will be a column in database.

Best Practice:
- all thing related to activity should be camel case.
- all thing related to data store (table & column) should be snake case.
- audit trail usually contains record from previous activity using the same form, created using subform.
- wrap beanshell logic in function
- customizing login form is done by hiding the default form, create new one and resonance the behavior to the default form
- styling is done using bootstrap & plain css
- add menu id on everything
- Put error on validation rather on next process, to minimize the burden.
- Don't use form grid validator plugin when possible, i.e when validating grand total of thing. instead use textfield validator on a calculation field.

Weird behavior:
- Javascript usage in custom HTML should be wrapped in a scope, otherwise it would throw redeclaration error when creating variable.
    This happen because Joget re-executing / re-rendering our custom HTML.
- When form field is readonly, the validation will never be executed.

