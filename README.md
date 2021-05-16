## New Zealand Tax Formula for Excel:

`=IF(B50<=14000,
B50*10.5%,
IF(B50<=48000,
(B50-14000)*17.5%+1470,
IF(B50<=70000,
(B50-48000)*30%+7420,
IF(B50<=180000,
(B50-70000)*33%+14020,
(B50-180000)*39%+50320))))`


**Disclaimer:**

Use this as is at your own risk. 
