
# TODO: 
1. Implement PayStrategy for PayByCreditCard and PayByPaypal
2. Implement pay and setSignedIn methods of PayByPaypal
3. Implement pay method of PayByCreditCard
4. Use strategy to make the payment in Main file

# Usage
Run: 
```bash
javac -d bin -sourcepath src src/*/*.java src/Main.java
java -cp ./bin Main
```


Final output should look like these:

```txt
Please, select a product:
1 - Mother board
2 - CPU
3 - HDD
4 - Memory
1
Count: 2
Do you wish to continue selecting products? Y/N: y
Please, select a product:
1 - Mother board
2 - CPU
3 - HDD
4 - Memory
2
Count: 1
Do you wish to continue selecting products? Y/N: n
Please, select a payment method:
1 - PalPay
2 - Credit Card
1
Enter the user's email: user@example.com
Enter the password: qwerty
Wrong email or password!
Enter user email: amanda@ya.com
Enter password: amanda1985
Data verification has been successful.
Pay 6250 units or Continue shopping?  P/C: p
Paying 6250 using PayPal.
Payment has been successful.
```
