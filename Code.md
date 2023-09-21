# Alphabetic-Telephone-Number-Translator
temp = input("Enter phone number: ")
phone = temp.upper()
#print(temp, len(temp), phone)
phoneDigits = " "
count = 0
while count < 12:
    if (phone[count] == "A")  or phone[count] == "B" or phone[count] == "C":
        phoneDigits += '2'
    elif (phone[count] == "D")  or phone[count] == "E" or phone[count] == "F":
        phoneDigits += '3'
    elif (phone[count] == "G")  or phone[count] == "H" or phone[count] == "I":
        phoneDigits += '4'
    elif (phone[count] == "J") or phone[count] == "K" or phone[count] == "L":
        phoneDigits += '5'
    elif (phone[count] == "0") or phone[count] == "N" or phone[count] == "O":
        phoneDigits += '6'
    elif (phone[count] == "P")  or phone[count] == "Q" or phone[count] == "R" or phone[count] == "S":
        phoneDigits += '7'
    elif (phone[count] == "T")  or phone[count] == "U" or phone[count] == "V":
        phoneDigits += '8'
    elif (phone[count] == "W")  or phone[count] == "X" or phone[count] == "Y" or phone[count] == "Z":
        phoneDigits += '9'
        count += 1
    else:
        phoneDigits += phone[count]
print(f"Digit phone number using \"while loop\": {phoneDigits}")
