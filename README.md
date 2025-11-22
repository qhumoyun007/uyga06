# uyga06
import math
#1
# cars={
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": "1979",
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# cars.update({"year":"2025"})
# print(cars)
# 2
# cars={
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": "1979",
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# cars.pop("made in...")
# print(cars)
# 3
# cars={
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": "1979",
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# del(cars["color"])
# print(cars)
# 4
# cars={
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": "1979",
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# cars.popitem()
# print(cars)
# 5
# cars = {
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": "1979",
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# cars.clear()
# print(cars)
# 6
# cars = {
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": "1979",
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# a=cars.get("model")
# print(a)
# 7
# cars = {
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": "1979",
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# for i in cars:
#     print(i)
# 8
# cars = {
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": "1979",
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# for i in cars.keys():
#     print(i, ":", cars[i])
# 9
# cars = {
#     "model": "Mersedes-Benz",
#     "seriya": "G-wagon",
#     "made in...": "Germaniya",
#     "year": 1979,
#     "color": "harbiycha, kulrang, oq, bej, ko'k, qora",
# }
# car = {
#     "model": "BMW",
#     "seriya": "X",
#     "made in...": "Germaniya",
#     "year": 1999,
#     "color": "alpine white, titanium silver, siena red, topaz blue, steel grey, pearl grey, pearl beige, oxford green2, mahogany brown, grey-green, black sapphire, jet black",
# }
# for i in car.values():
#     for j in cars.keys():
#        print(j,":",i)
# 10
# car = {
#     "model": "BMW",
#     "seriya": "X",
#     "made in...": "Germaniya",
#     "year": 1999,
#     "color": "alpine white, titanium silver, siena red, topaz blue, steel grey, pearl grey, pearl beige, oxford green2, mahogany brown, grey-green, black sapphire, jet black",
# }
# a=car.copy()
# car.clear()
# print(a)
# print(car)
# 11
# car = {
#     "model": "BMW",
#     "seriya": "X",
#     "made in...": "Germaniya",
#     "year": 1999,
#     "color": "alpine white, titanium silver, siena red, topaz blue, steel grey, pearl grey, pearl beige, oxford green2, mahogany brown, grey-green, black sapphire, jet black",
# }
# a=car.setdefault("seriya")
# print(a)
# 12
# car = {
#     "model": "BMW",
#     "seriya": "X",
#     "made in...": "Germaniya",
#     "year": 1999,
#     "color": "alpine white, titanium silver, siena red, topaz blue, steel grey, pearl grey, pearl beige, oxford green2, mahogany brown, grey-green, black sapphire, jet black",
# }
#
# x = car.setdefault("color", "White")
#
# print(x)
