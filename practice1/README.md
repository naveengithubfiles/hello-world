def pal(num):
    xl = num[::-1]
    if xl == num:
        print('palindrom')
    else:
         print('not a palindrome')

print(pal('madam'))
