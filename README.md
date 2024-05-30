## New Zealand Tax Formula for Excel:

(Replace `B50` with the cell where you input your income amount)

**From August 2024 - present**

`=IF(B50<=15600, B50*10.5%, 
IF(B50<=53500, (B50-15600)*17.5%+1638, 
IF(B50<=78100, (B50-53500)*30%+7075.5, 
IF(B50<=180000, (B50-78100)*33%+15060.5, (B50-180000)*39%+49747.5))))`

____

**Up to end of July 2024**

`=IF(B50<=14000, B50*10.5%,
IF(B50<=48000, (B50-14000)*17.5%+1470,
IF(B50<=70000, (B50-48000)*30%+7420,
IF(B50<=180000, (B50-70000)*33%+14020, (B50-180000)*39%+50320))))`

___

**Disclaimer:**

Use this as is at your own risk.
