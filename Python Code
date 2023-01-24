# Store the hours worked
hours_worked = float(input("{:<40}".format("Enter the number of hours worked: ")))

# Store the days worked
days_worked = float(input("{:<40}".format("Enter the number of days worked: ")))

# Store the hourly rate
hourly_rate = float(input("{:<40}".format("Enter the hourly rate: ")))

# Store the holidays per year
holidays_off = float(input("{:<40}".format("Enter the number of holiday days: ")))

# Store the vacation days off
vacation_off = float(input("{:<40}".format("Enter the number of vacation days: ")))

# Calculate the unadjusted salary
unadjusted_salary = hours_worked * hourly_rate * days_worked

# Calculate the adjusted salary
adjusted_salary = unadjusted_salary - ((holidays_off + vacation_off)*(hourly_rate * hours_worked))

# Round the unadjusted salary
rounded_unadjusted = "{:.2f}".format(unadjusted_salary)
rounded_adjusted = "{:.2f}".format(adjusted_salary)

# Print the results
print("Unadjusted salary:", rounded_unadjusted)
print("Adjusted salary:", rounded_adjusted)
