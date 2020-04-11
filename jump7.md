for a in range(1,101):
	while a  <= 100 :
		b=a
		if b%7 != 0 and b%10 != 7 and b // 10 != 7:
			print(a)
		a+=1
	break
