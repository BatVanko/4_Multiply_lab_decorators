# 4_Multiply_lab_decorators
Having the following code:
def multiply(times):

    def decorator(function):

        # TODO: Implement

    return decorator
Complete the code, so it works as expected.
Test Code
@multiply(3)
def add_ten(number):
    return number + 10

print(add_ten(3))
Output
39

Comment
First, we add 3 to 10 = 13, and then we multiply the result by 3: 13 * 3 = 39
