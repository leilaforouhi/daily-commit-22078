def separate_even_odd(number):
    evens = [n for n in numbers if n % 2 == 0]
    odds = [n for n in numbers if n % 2 != 0]
    return evens, odds

if __name__ == "__main__":
    nums = [11, 22, 33, 44, 55, 66]
    even_list, odd_list = separate_even_odd(nums)
    print(f"Evens: {even_list}")
    print(f"Odds: {odd_list}")

