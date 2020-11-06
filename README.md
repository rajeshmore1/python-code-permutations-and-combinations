# python-code-permutations-and-combinations
Permutations and Combinations Code Python
#COMBINATIONS:-
def factorial(n):
  f = 1
  for i in range(1, n+1):
    f = f * i
  return f
def C(n, r):
  return int(factorial(n)/(factorial(r) * factorial(n-r)))
  
  #Permutations
  
  def factorial(n):
  f = 1
  for i in range(1, n+1):
    f = f * i
  return f
  
  def P(n, r):
  return int(factorial(n)/factorial(n-r))
  
  C(10,4)= 5040
