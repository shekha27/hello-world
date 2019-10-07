# hello-world
def is_even(number):
    '''
    (number) -> bool
    The function returns True if the input parameter (number) is even and False if the input parameter (number) is odd.
    >>> is_even(3)
    False
    >>> is_even(2)
    True
    '''
    if number%2 == 0:
        return True
    else:
        return False


print(is_even(3))
print(is_even(2))
