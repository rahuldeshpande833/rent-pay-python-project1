# rent-pay-python-project1
No of members who lives together to pay equal amount of bills / rent amount.

# ROOM RENT PAY PROJECT

#Include
'''
1.No of memebrs living in a room ?
2.Zomato food bill amount ordered in month ?
3.Electricity amount unit consumed ?
4.Aria wise unit charges per unit ?
5.No of Rooms used ?'''


Members = int(input("Enter your No of Members ?: "))
zomato_amt = int(input("Enter your order food amount ?: "))
Electricity_Bill_amt = int(input("Electricity amount unit consumed ?: "))
Per_unit_amt = int(input("Aria wise unit charges per unit ?: "))
rooms_used = int(input("No of Rooms used ?: "))

total =  Electricity_Bill_amt  * Per_unit_amt + Members + zomato_amt + rooms_used

print(total)
