### common

| status code | resson         |
| ----------- | -------------- |
| 0           | no error       |
| 101         | not authorized |
| 102         | failure        |
| 103         | params error   |
| 999         | unknown error  |

### cdnUserRequest /cdn/*action

| status code | resson         |
| ----------- | -------------- |
| 201           | bind name not exist       |
| 202           | bindDomain is off       |
| 203           | not enough balance       |

### /client/newdomain

<!-- 10xx -->

| status code | resson                  |
| ----------- | ----------------------- |
| 1001        | bind name already exist |
| 1002        | originUrl already exist |

### /client/modifydomainstate

<!-- 11xx -->

| status code | resson              |
| ----------- | ------------------- |
| 1101        | domain id not exist |

### /client/deletedomain

<!-- 12xx -->

| status code | resson              |
| ----------- | ------------------- |
| 1201        | domain id not exist |

### /client/getdomains

<!-- 13xx -->

| status code | resson |
| ----------- | ------ |
| 1301        | 12345  |

### /client/traffic

<!-- 14xx -->

| status code | resson |
| ----------- | ------ |
|             |        |

### /client/getdepositrecord

<!-- 15xx -->

| status code | resson |
| ----------- | ------ |
|             |        |

### /client/depositaddr

<!-- 16xx -->

| status code | resson |
| ----------- | ------ |
|             |        |

### /client/getbalance

<!-- 17xx -->

| status code | resson |
| ----------- | ------ |
|             |        |

### /terminal/getmachineinfo

<!-- 18xx -->

| status code | resson |
| ----------- | ------ |
|             |        |

### /terminal/profit

<!-- 19xx -->

| status code | resson |
| ----------- | ------ |
|             |        |

### /user/register

<!-- 20xx -->

| status code | resson                 |
| ----------- | ---------------------- |
| 2001        | username already exist |
| 2002        | email already exist    |
| 2003        | phone already exist    |

### /user/login

<!-- 21xx -->

| status code | resson                     |
| ----------- | -------------------------- |
| 2101        | username not already exist |
| 2102        | email not already exist    |
| 2103        | phone not already exist    |
| 2104        | password error             |