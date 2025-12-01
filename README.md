# Euclidean-Algorithm
class Euclidean Algorithm GCD:
def_init_（self）:
def GCD(self, A,B):
    self.A=A
    self.B=B
    if A ==0 and B == 0:
        print("error A and B can't be 0 at same time")
    if A < 0 or B < 0:
        print("error A and B can't be negative")
    while b !=0 and B > A:
        remainder = A%B
        A=B 
        B=remainder
    return A
    
    
        
 
