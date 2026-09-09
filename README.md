[README 7.md](https://github.com/user-attachments/files/31996782/README.7.md)
```python
age = int(input("Enter your age: "))
if age >= 18:
    print("Eligible for IPL ticket booking")
else:
    print("Not eligible")
```

```python
number_of_followers = int(input("enter the number of followers: "))
if number_of_followers < 10000:
    print("Micro Influencer")
elif number_of_followers >= 10000 and number_of_followers <= 100000:
    print("Rising Star")
else:
    print("Celebrity")
```

```python
total_amount = int(input("Enter the total amount: "))
if total_amount > 299:
    print("Apply Free Delivery")
elif total_amount >= 200 and total_amount <= 299:
    print("Add more items for free delivery")
else:
    print("Delivery charges apply")
```

```python
# Write a Python program using nested if statements: take a user's entered Flipkart cart value and payment method ('UPI', 'Card', 'Cash').
# If the cart value is above 1000 and payment method is 'UPI', print 'Eligible for 10% cashback';
# if above 1000 and payment is not 'UPI', print 'Eligible for 5% cashback'; else print 'No cashback'
```

```python
Flipcart_cart_value = int(input("Enter the Flipkart cart value: "))
payment_method = input("Enter the payment method: ")
if Flipcart_cart_value > 1000:
    if payment_method == "UPI":
        print("Eligible for 10% cashback")
    else:
        print("Eligible for 5% cashback")
else:
    print("No cashback")
```
