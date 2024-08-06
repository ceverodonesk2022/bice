# bice
# Sample list of items (assuming they have attributes, such as type)
items = [
    {'type': 'bike', 'color': 'red'},
    {'type': 'skateboard', 'color': 'blue'},
    {'type': 'bike', 'color': 'green'},
    {'type': 'bike', 'color': 'blue'},
    {'type': 'scooter', 'color': 'red'}
]

# Count the number of bikes
num_bikes = sum(1 for item in items if item['type'] == 'bike')

print(f"Number of bikes: {num_bikes}")
num_bikes
