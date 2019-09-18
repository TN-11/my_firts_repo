# my_firts_repo
# A Python program for Arithmetic Progression
def AP(x,y,z):
	first_term=int(x)
	Number=int(y)
	difference=int(z)
	
	Answer= first_term + (number-1)*difference
	print("The nth term is:", Answer)
	return
	
while True:
	a=input("Enter First Term; ")
	b=input("Enter Number of Terms; ")
	c=input("Enter Common Difference; ")
	AP(a,b,c)
