# cognifyz-internship-1
name = input(("enter string : "))
length = len(name)
i = 0
for n in range(-1, (-length - 1), -1):
    print(name[i], "\t", name[n])
    i += 1
