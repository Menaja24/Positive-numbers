# Positive-numbers
def print_positive_numbers(input_list):
    positive_numbers = [num for num in input_list if num > 0]
    print(positive_numbers)
list1 = [12, -7, 5, 64, -14]
list2 = [12,14,-95,3]
print("Input:", list1, "Output:", end=" ")
print_positive_numbers(list1)
print("Input:", list2, "Output:", end=" ")
print_positive_numbers(list2)
