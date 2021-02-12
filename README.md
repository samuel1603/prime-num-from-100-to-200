# prime-num-from-100-to-200
for num in range(100,200):
	if all(num!=0 for i in range (2,num)):
		print(num)
