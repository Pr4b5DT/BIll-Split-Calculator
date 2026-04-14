# BIll-Split-Calculator
# just a basic python codes
print("Bill Split Calculator")
bill_amt = float(input())
tip_per = float(input())
num = int(input())
tip_amt = (tip_per/100)*bill_amt
total = tip_amt + bill_amt
print(f"Total (including tip): ${total}")
amt_pp = total/num
print(f"Each person pays: ${amt_pp}")
