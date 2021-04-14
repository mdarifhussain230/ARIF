import random
lower=("abcdefghijklmnopqrstuvwxyz")
upper=("ABCDEFGHIJKLMNOPQRSTUVWXYZ")
number=("0123456789")
all=lower+upper+number
password=random.sample(all,8)
print(password)
