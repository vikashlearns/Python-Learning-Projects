# Determine the ticket price based on age and whether the person is a student or not.

age=int(input("Enter your age: "))
is_student=input("Are you a student? (yes/no): ").strip().lower()
if age < 5:
    price = "Free"   
elif age <= 12:
    price= "$10"
elif age <= 17:
    if is_student == "yes":
        price = "$12"
    else:
        price = "$15"
elif age <= 64:
    if is_student == "yes":
        price = "$18"
    else:
        price = "$25"
else:
            price = "$20"
print(f"The ticket price is: {price}")








