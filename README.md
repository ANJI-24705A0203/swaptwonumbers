# swaptwonumbers
def swap_numbers(a, b):     print(f"Original: a = {a}, b = {b}")          # Pythonic swap: No temporary variable needed     a, b = b, a          print(f"Swapped:  a = {a}, b = {b}")     return a, b  if __name__ == "__main__":     # Example usage     num1 = 10     num2 = 20     num1, num2 = swap_numbers(num1, num2)
