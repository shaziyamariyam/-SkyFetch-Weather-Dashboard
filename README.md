#  JS Fundamentals – Banking Utility  

## About the Question  
You are working on a **Banking Application**. Your task is to implement simple functions that help manage **account balances**. You’ll use **variables, conditionals, operators, and functions** to complete this assignment.  

---

## Tasks  
1. Create a variable `accountHolder` to store the name of the customer.  
-  Initial account details:
- var accountHolder = "John Doe";

2. Create a variable `balance` to store the current account balance (in numbers). 
- Initial account details:
- var balance = 1000; 

3. Write a function `deposit(amount)` that adds the given amount to the balance and returns the updated balance.  
4. Write a function `withdraw(amount)` that deducts the given amount from the balance, only if sufficient funds are available:  
   - If withdrawal amount is **less than or equal** to balance, subtract and return updated balance.  
   - If withdrawal amount is **greater** than balance, return `"Insufficient Funds"`.  
5. Write a function `checkBalance()` that simply returns the current balance.  

**Note:**
Initial balance is reset to 1000 before each test.

---

## Test Cases (7 total)  
- `deposit` should add money and return updated balance.  
- `withdraw` should deduct money when funds are sufficient.  
- `withdraw` should return `"Insufficient Funds"` if amount is greater than balance.  
- Multiple deposits should update the balance correctly.  
- Multiple withdrawals should update the balance correctly.  
- `checkBalance` should return the correct balance after transactions.  
- Edge case: withdrawing the exact balance should leave the balance at `0`.  

---

## Submission Guidelines  
- Write your solution in `src/app.js`.  
- Do not change the test file.  
- Run the Jasmine test cases to validate your solution.  


---

**Good Luck!**
