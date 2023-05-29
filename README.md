# WebForm
  
A web form for gathering info on someone.  
Last update: 30/05/2023

---

### The form fields are:

1. **First name**  
    _Every combination of character is considered valid_

    > Field is required[^1]

2. **Last name**  
    _Every combination of character is considered valid_

    > Field is required[^1]

3. **Date of birth**  
    _`dd/mm/yyyy` format_

    > Field is required[^1]

4. **Sex**  
    _Selection between:_  

    - _`Male`_
    - _`Female`_
    - _`Other`_

    > Field is required[^1]

5. **Is alive**  
    _Selection between:_  

    - _`Yes`_
    - _`No`_

    > Field is required[^1]

6. **Number of children**  
    _Every number between `0` and `99` is considered valid_

    > Field is required[^1]

7. **E-mail**  
    _No validity check_

8. **Phone number**  
    _No validity check_

    >Field does not account properly for phone numbers with `plus sign` and/or `space`.

9. **More information**  
    _No validity check_

---

```
Note:  
    
Phone number field will be updated shortly to account for phone numbers properly.
```


[^1]: The required fields show a red underline when invalid or empty.