def final_quiz_score(scores):
    # Ensure there are more than two scores to remove the highest and lowest
    if len(scores) > 2:
        scores.sort()
        # Remove the lowest and the highest scores
        scores = scores[1:-1]
    # Calculate the sum of the remaining scores
    return sum(scores)

# Example scores
scores = [8, 7, 8.5, 9.5, 7, 5, 10]

# Calculate and print the final score
final_score = final_quiz_score(scores)
print("Final Quiz Score:", final_score)
