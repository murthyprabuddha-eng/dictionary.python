# dictionary.python
cricket={
    "virat":"batsman",
    "dhoni" : "captain",
    "rohith": "opener",
}
print(cricket.get("virat","not found"))#op:batsman
print(cricket.get("sachin","not found"))
''' out put not found because
the dictionary cricket does'nt contain sachin here'''

cricket["sachin"]="GOAT",#adding sachin to the dictionary
print(cricket["sachin"])#op:('GOAT',)

cricket.pop("rohith") # removing rohith from the dictionary
print(cricket)#{'virat': 'batsman', 'dhoni': 'captain', 'sachin': ('GOAT',)}

'''cricket.clear() 
print(cricket)''' #clear() is used delete entire dictionary list

''' making list of dictionary and printing'''

item1={
    "name":"coke",
    "quantity":1,
    "price":40,
}

item2={
    "name":"cake",
    "quantity":4,
    "price":160,
}
items=[item1,item2]
print(items)

print(item1["price"]+item2["price"])#op:200


