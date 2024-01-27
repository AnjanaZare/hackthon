# hackthon
def calculate_pizza_count(individuals):
    
    large_slices = 8
    medium_slices = 6
    regular_slices = 4
    small_slices = 1

    
    large_pizzas = individuals 
    individuals %= large_slices

    medium_pizzas = individuals 
    individuals %= medium_slices

    regular_pizzas = individuals 
    individuals %= regular_slices

    small_pizzas = individuals 

    
    print(f"We will have {large_pizzas} Large pizza")
    print(f"We will have {medium_pizzas} Medium pizza")
    print(f"We will have {regular_pizzas} Regular Pizza")
    print(f"We will have {small_pizzas} Small Pizza")

    
    total_slices = (large_pizzas * large_slices) + (medium_pizzas * medium_slices) + \
                   (regular_pizzas * regular_slices) + (small_pizzas * small_slices)
    print(f"Total slices: {total_slices}")



calculate_pizza_count(100)
print("-----------------------------------------------------------")
calculate_pizza_count(19)
