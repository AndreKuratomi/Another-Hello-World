# The young indian boy's request with Python.

""""As I'm new here in GitHub I decided to try to code that indian story of the young man, the king, the chess border and the rice seeds.

The young man asked the king to put one seed of rice in the first square and multiply it by 2 in the second one, and on the third the amount of the second multiplied by 2 again and so on till the 64th square. The result of the young man's request, 2 raised by 63 (first square with just 1 seed), will be almost 10 quintillions of seeds! 

How to turn this on code? How to create a little code which you write the number of the square and the code will return the amount of seeds in that square?

Here's my attempt to solve this using Python. Good luck for me!"""

class RiceSeedsOnChess:

	def __init__(self, square): """square = square number on chess border"""
	
		self.square=square
		
	def amount(self): """amount = amount of rice seeds at the square number"""
	
		return 2**(self.square-1)
		
	if square>64:
	
		raise ValueError1("OUT OF THE CHEZ BORDER!")
		
	if square<1:
	
		raise ValueError2("OUT OF THE CHEZ BORDER!")
