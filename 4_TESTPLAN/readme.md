# TEST PLAN:

## HIGH LEVEL TEST PLAN:
| **TEST ID**|**DESCRIPTION**|**EXP I/P**|**EXP O/P**|**ACTUAL O/P**|**TYPE OF TEST**|
|-----|-------|-----|-----|-----|------|
|H_01| Registration /signup|Name:___ | Registration success| Registration success| Requirement based|
|     |           | Father Name:___ |      |    |       |
|     |     | DOB:___ |       |       |       |
|     |     | Sex:___ |     |       |       |
|      |     | Div:___ |      |     |       |
|   |    |Disct:___ |      |     |     |
|       |     |State:___ |      |       |
|H_02| Login 1| Username:___ Password:___ | Login success| Login success | Scenario based|
|H_03| New election initialization| Branch code:___ Roll no:___ No. of candidadtes: 2 | Files saved / Please vote | Please vote | Scenario based |
|H_04| Candidate ID  | 063548_A021 | Done| Done| Boundary based|
|H_05| Candidate ID | 063549_A024| Successfully voting is done| Successfully voting is done| Boundary based|
## LOW LEVEL TEST PLAN:
|**TEST ID**|**DESCRIPTION**|**EXP I/P**|**EXP O/P**|**ACTUAL O/P**|**TYPE OF TEST**|
|-----|-----|-----|----|----|------|
|L_01| Signup|If any wrong details entered| Please give the valid details| Invalid details entered| Requriment based|
|L_02| Login 2/ Case if password is forgot| Username: Forgot password: Reset password: | Generated password successfully | Generated password successfully| boundary based|
|L_03| Submission of vote| Submit| Submitted| Submitted| Boundary based|
|L_04| Admin login| Username:___ Password:___ | Reviewed the votes| Reviewed the votes| Scenario based|
|L_05| Admin| Count view| No of votes generated: 7556546| No of votes generated: 7556546| Requirement based|
                        
                        
                         


