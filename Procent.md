per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
money = input("Введите сумму :")
z = (int(money)/100)
y = (list(per_cent.values()))
deposite = [z*float(y[0]),z*float(y[1]),z*float(y[2]),z*float(y[3])]
print("deposite =",deposite)
print("Максимальная сумма, которую вы можете заработать — ",max(deposite))
