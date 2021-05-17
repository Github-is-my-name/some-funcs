# some-funcs
Just some functions 
def euclid (a,b):
	r = None
	while r != 0 :
		if a > b : q = a//b ; r = a - b*q 
		else : a,b = b,a ; q = a//b ; r = a - b*q 
		print('{}={}*{}+{}format(a,b,q,r))
		if r != 0 : a = b ; b=r 
		return 'The HCF is {}'.format(b)
		
