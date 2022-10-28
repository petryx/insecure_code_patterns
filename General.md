
## Rules for code review

### User Controlled Parameters

    1 - Always look for user-controlled parameters.
    2 - Follow the variables that have user-controlled data.
    3 - Check if the variable is sanitized
    4 - If the variable is sanitized, check if it is possible to bypass the sanitization function



## Sql Injection (SQLi)

### Regex

- ^.*?select.*?where.*?\+
- select.*from.*\+
- where.+\+
- .*update.*SET.*=.*\+
- .*select\s+.*\s+from .*
- .*update\s+.*\s+where
- .*insert\s+.*\s+
- .*delete\s*.*\s+from

#### REGEX SQL with string concatenation

- ^.*?select.*?where.*?\+.*\+.*? 

## URL Parameters

- url
- href
- cmd
- id
- path
- file
- dir


## Hardcoded

- Password
- IP address
- Email
- Special Hotkey
- URL 
- Mobile Number
- Name
- Client API Secret
- Client API Key
- Token

## Forms
- hidden fields
