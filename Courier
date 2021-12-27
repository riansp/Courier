name = input('Input your name: ')
from os import system
a_go = []
a_to = []
a_distance = []
a_gas = []

print('='*126)
print('  Hei', name,                                                                                                                  )
def menu():
    system('cls')
    print('====================================='.center(120))
    print('Input delivery data'.center(120))
    print('====================================='.center(120))
    print('| 1. Input Data                   |'.center(120))
    print('| 2. Show Data                    |'.center(120))
    print('| 3. Done                         |'.center(120))
    print('====================================='.center(120))
    select = input('Select Menu: ')
    if select == '1':
        add()
    elif select == '2':
        show(), total()
    elif select == '3':
        done()
    else:
        none = input('Option None: ')
        system('cls')
        menu()

def add():
    system('cls')
    go = input('From where: ')
    a_go.append(go)
    to = input('Where to go: ')
    a_to.append(to)
    
    system('cls')
    distance = float(input('How Distance: '))
    b_gas = distance/(2.5*1)
    a_distance.append(distance)
    a_gas.append(b_gas)
    print ('saved data'.center(40))
    
    select = input('Select Menu: ')
    if select == '1':
        add()
    elif select == '2':
        show(), total()
    elif select == '3':
        done()
    else:
        none = input('Option None: ')
        system('cls')
        menu()
def show():
    system('cls')
    for i in range (len(a_go)):
        print('--------------------------------')
        print('    From        : %s'%a_go[i])
        print('    To          : %s'%a_to[i])
        print('    Distance    : %s'%a_distance[i], 'KM')
        print('    Gas         : %.2f'%a_gas[i], 'L')
        print('--------------------------------')
def total():
    system('cls')
    tj = round(sum(a_distance), 2)
    tb = round(sum(a_gas), 2)
    ppj = round(tj * 2, 2)
    ppb = round(tb * 2, 2)
    print('    Total Distance       : ',tj, 'KM')
    print('    Total Gas            : ',tb, 'L')
    print('    Estimasi Distance PP : ',ppj, 'KM')
    print('    Estimasi Gas PP      : ',ppb, 'L')
    print('')
    print('*Assumption 1 L of fuel can be used as far as 2.5 KM')
    kembali = input('Back Press [Enter]')
    menu()

def done():
    system('cls')

menu()
print('Stay Safe and Be Careful',nama)
