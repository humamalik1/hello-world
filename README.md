# hello-world

# Hello World program in Python
    
print "Hello World!\n"
#
[]
lottery = [3 , 4 , 33, 4412, 1, 22, 11]
len(lottery)
lottery.append(3009)
lottery.sort()
lottery.pop(3)
print(lottery)
#
{}
participant = {'name': 'Ola', 'country': 'Poland', 'nos': [7, 42, 92]}
print(participant['nos'])
participant['favorite_language' ]= 'Python'
len(participant)
participant.pop('nos')
[7, 42, 92]
participant['country'] = 'Germany'
print(participant)
# next
a = 5 < 3
print (a)
# next
if 5 > 2:
    print('5 is indeed greater than 2')
else:
    print('5 is not greater than 2')
# next
def hi():
    print('Hi there!')
    print('How are you?') 
# next
hi()

def hi(name):
    print('Hi ' + name + '!')

hi('rachel')
# next

def hi(name):
    print('Hi ' + name + '!')

girls = ['Rachel', 'Monica', 'Phoebe', 'Ola', 'You']
for name in girls:
    hi(name)
    print('Next girl')
# next
for i in range(1, 100):
    print(i)
