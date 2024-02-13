# Discount-py-
t=int(input())
for _ in range(t):
  a,b,c,d=map(int,input().split())
  f=a-c
  s=b-d
  if f>s:
    print("second")
  elif f<s:
    print("first")
  else:
    print("any")
