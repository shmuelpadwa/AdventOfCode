nums = []
for i in range(168630,718098): 
  nums.append(str(i))

passedfirst = []
for item in nums:
  if list(item) == sorted(item):
    passedfirst.append(item)

passedsecond = []
for number in passedfirst:

  for digit in number:
    count = number.count(digit)
    if count >= 2:
      passedsecond.append(number)               
      break  

print(len(passedsecond))

#for part two, switch the >= in line 15 to ==
