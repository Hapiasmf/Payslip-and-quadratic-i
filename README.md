# Payslip-and-quadratic-i
START
INPUT FLOAT hourlyPayRate 
INPUT FLOAT hoursWorked 
grossPay = hourlyPayRate * hoursWorked 
OUTPUT grossPay 
STOP 

.. 
.. 


START
INPUT FLOAT hourlyPayRate
INPUT FLOAT hoursWorked
INPUT taxRate
grossPay = hourlyPayRate * hoursWorked
netPay = grossPay * (100-taxRate/100)
OUTPUT netPay
STOP

..
..
