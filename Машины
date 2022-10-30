cars = ["Kia", "Audi", "Aston Martin", "BMW"]
prices = [20000, 40000, 100000, 60000]
it = dict(zip(cars, prices))
print(it)
import csv
with open("cars.csv", "w", encoding='utf-8') as f:
    writer = csv.writer(f, delimiter=';', lineterminator="\r")
    writer.writerow(["cars", "prices"])
    for i in range(2):
        row = [cars[i], prices[i]]
        writer.writerow(row)

with open("text.txt") as f:
    count = f.read().count('a')
print(count)
