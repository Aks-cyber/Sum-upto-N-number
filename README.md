# Sum upto N numbers.
# n = 5
# 1+2+3+4+5 = 15
# n = 10
# 1+2+3+4+5+6+7+8+9+10 = 55
def first_sum(n):
    #0(1) 0 at 1 attempt only
    return (n)*(n+1) // 2

def second_sum(n):
    sum = 0
    for i in range(1,n+1):    #[1,n]
        sum = sum + i
    return sum


t = int(input())      #Test case
while t:
    n = int(input())
    print('sum executed output : {}'.format(sum1(n)))
    print('sum executed output : {}'.format(sum2(n)))
    t=t-1
