def block_seven_and_show_message(number):
    number_str = str(number)
    result = ""
    for digit in number_str:
        if digit == '7':
            result += "Nathishya I love you 💕💓"
        else:
            result += digit
    return result

# Example usage
number = 1234567890
print(block_seven_and_show_message(number))
