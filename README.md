# Get input for the first exam score
exam1_score = float(input("Enter the score for the first exam:"))
# Get input for the second exam score
exam2_score = float(input("Enter the score for the second exam:"))
# Calculate the weighted total score
# First exam is worth 60%, second is worth 40%
total_score = (exam1_score * 0.60) + (exam2_score * 0.40)
# Display the total score, formatted to two decimal places
print(f"The total weighted score is:
{total_score:.2f}")
