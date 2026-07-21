lst_gasto= []
print ("Welcome to the Daily Expense Tracker!")
print ()
print ("Menu:")
Lst_menu = ["Add a new expense", "View all expenses", "Calculate total and average expense", "Clear all expenses", "Exit"]
for index, elemento in enumerate(Lst_menu, start=1):
    print(f"{index}. {elemento}")
while True:
    choice = int(input()) 
    if (choice == 1):
        valor=float(input())
        lst_gasto.append(valor)
        print("Expense added successfully!")
    elif (choice == 2):
        if (lst_gasto == []):
            print("No expenses recorded yet.")
        else:
            print("Your expenses:")
            for index, gasto in enumerate(lst_gasto, start=1):
                print(f"{index}. {gasto}")
    elif (choice== 3):
        if (lst_gasto == []):
            print("No expenses recorded yet.")
        else:
            suma_Gasto = 0
            for gasto in lst_gasto:
                suma_Gasto += gasto
            promedio_Gasto = suma_Gasto / len(lst_gasto)
            print(f"Total expense: {suma_Gasto}")
            print(f"Average expense: {promedio_Gasto}")
    elif (choice == 4):
        lst_gasto.clear()
        print("All expenses cleared.")
    elif (choice == 5):
        print("Exiting the Daily Expense Tracker. Goodbye!")
        break
    else:
        print("Invalid choice. Please try again.")
