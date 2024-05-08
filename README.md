# java script regex validate !

## js regex

#### email
    email_regex:  /^\w+([\.-]?\w+){2,}@\w+([\.-]?\w+){3,}(\.\w{2,3})+$/
#### username
    username_len:  /^[a-zA-z0-9]{4,}$/
    username_regex:  /^[-\w\.\$@\*\!]{4,30}$/
#### password
    password_regex:  /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[A-Za-z\d@$!%*?&]{8,}$/
#### economicId
    economicId_len:  /^[0-9]{11,14}$/
    economicId_regex:  /^(?!(\d)\1)\d{11,14}$/
#### nationalCode
    nationalCode_len:  /^[0-9]{10}$/
    nationalCode_regex:  /^(?!(\d)\1{2})\d{10}$/
#### nationalId
     nationalId_len:  /^[0-9]{11}$/
     nationalId_regex:  /^(?!(\d)\1{2})\d{11}$/
#### cellPhone
    cellPhone_regex:  /^09[0-9]{9}$/
#### taxID
    taxID_len:  /^[0-9]{7,10}$/
#### zipCode
    zipCode_len:  /^[0-9]{9,10}$/
#### phoneNumber
    phoneNumber_len:  /^[0-9]{5,}$/
