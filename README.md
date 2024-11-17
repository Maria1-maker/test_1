# test_1

##Репрозитоий

def change(str):
    s = [str[0].upper()]
    for c in str[1:]:
        if c in ('ABCDEFGHIJKLMNOPQRSTUVWXYZ'):
            s.append(' ')
            s.append(c.upper())
        else:
            s.append(c)
     
    return ''.join(s)
    
str = input('')
print(change(str))
