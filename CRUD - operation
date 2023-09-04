dictt = {
    'Alex': 4,
    'Mika': 8,
    'Artem': 9,
    'Vasil': 12
}
def Print():
    for i, j in dictt.items():
        print(f"\n{i} - {j}")
def Delete():
    name = input('\nGive a name, that you want to delete -> ')
    del dictt[name]
    for i, j in dictt.items():
        print(f"{i} - {j}\n")
    print(f"\n{name} success deleted...\n")
def Add():
    name = input('\nGive a name, that you want to add -> ')
    number = int(input(f"\nGive a mark for a {name} -> "))
    dictt[name] = number
    for i, j in dictt.items():
        print(f"{i} - {j}\n")
    print(f"\n{name} success added...")
def Update():
    name = input('\nGive a name, that you want to update -> ')
    number = int(input(f'\nGive a mark for a {name} -> '))
    dictt[name] = number
    for i, j in dictt.items():
        print(f"{i} - {j}\n")
    print(f"\n{name} success updated...")
while True:
    x = int(input("\nGive one of the operations:\n*1* - Take students out\n*2* - Delete a pupil\n*3* - Add a pupil\n*4* - Update mark for a pupil\n*0* - Break this operation\nGive a number here -> "))
    if x == 1:
        Print()
    elif x == 2:
        Delete()
    elif x == 3:
        Add()
    elif x == 4:
        Update()
    elif x == 0:
        break
