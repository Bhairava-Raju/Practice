//to find the 37th number divisible by seven which have only odd digits
def abc():
    mul=0
    a=0
    i=1
    while a<37:
        mul=7*i
        num=mul
        r=1
        while num>0:
            if num%2==0:
                r=0
                break
            num=num//10
        if r==1:
            a+=1
        i+=1
    print(mul)
abc()
