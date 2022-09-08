## Overview

Thank you for looking at our Firmware Technical Exercise, we ask that you create a solution to the following, we don't expect it to take longer than two hours and submission can be via either forking this repository or via emailing a zip with your solution included.

## JSON payloads and array de-duplication

Write a program in C (C99) to parse a JSON payload containing an array, remove the duplicate elements from the array and output a JSON payload containing the de-duplicated array.

**Input**

```
{"readings": [10, 20, 10, 1, 100, 10, 2, 1, 5, 10]}
```

**Expected output**

```
{"output": [10, 20, 1, 100, 2, 5]}
```

### Constraints

* You must use the cJSON library for parsing and constructing JSON payloads.
* Any memory allocated must be freed after printing the output JSON payload.
* You may use any testing strategy and libraries you deem appropriate.
* A Makefile must be provided which will build an executable of the main program as a minimum.
