# Implement a Basic Banking System

Problem Statement 
A banking application needs a basic system to manage customer accounts. The system should 
allow users to: 
Create a bank account by providing the account holder's name, account number, and initial 
balance. 
Deposit a specified amount into the account. 
Withdraw a specified amount from the account (only if sufficient balance is available). 
Display the final balance after performing the above operations. 
The application should ensure that the account balance remains valid throughout the operations 
and adheres to defined input constraints. 
 
Input Format 
The program will read five inputs in the following order: 
Account holder name A string (can include spaces) 
Account number - An integer 
Initial balance - A double 
Deposit amount - A double 
Withdrawal amount A double 
Note: All inputs are read from standard input (Scanner) 
 
Output Format 
The output should be: 
If all transactions are successful (i.e, the withdrawal is allowed), print the final balance as a 
double. 
If the withdrawal amount is greater than the available balance, print: Insufficient balance 
If any input value is invalid (e.g., negative deposit/withdrawal or non-positive account number), 
print: Invalid Input values. 
 
Constraints 
accountNumber > O 
initialBalance >= 0 
depositAmount >= 0 
withdrawAmount >= 0 
withdrawAmount <= currentBalance (Only if withdrawal should happen) 
 
Sample Test Case 1 
Input: 
Bob 
123486 
282 
2000 
2500 
Output: 
Insufficient balance 
 
Sample Test Case 2 
Input: 
John Doe 
123456 
5000 
1500 
2000 
 
Output: 
4500.0 
 
Explanation: 
Initial balance: 5000 
After deposit: 6500 
After withdrawal: 6500-2000 = 4500 
