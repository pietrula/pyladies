# pyladies
dane=[input('podaj imię członka rodziny'), input("podaj mase:"), input('podaj wzrost:'), input('podaj plec:')]
BMI=(float(dane[1])/(float(dane[2])**2))
if "kobieta" in dane[3]:
	if BMI <16.5:
		print(dane[0], "anoreksja");
	elif 16.5 < BMI < 20:
		print(dane[0], 'niedowaga');
	elif 20 < BMI < 25:
		print("norma");
	elif 25 < BMI < 30:
		print(dane[0], "nadwaga");
	else:
		print(dane[0], 'otylosc');
if "mezczyzna" in dane[3]:
	if BMI <18.5:
		print(dane[0], "anoreksja");
	elif 18.5 < BMI < 22.5:
		print(dane[0], 'niedowaga');
	elif 22.5 < BMI < 27.5:
		print(dane[0], "nadwaga");
	elif 27.5 < BMI < 32.5:
		print(dane[0], "norma");
	else:
		print(dane[0], 'otylosc');
pytanie=(input('czy chcesz poznać BMI kolejnego członka rodziny?'))
while pytanie=='tak':
  dane=[input('podaj imię członka rodziny'), input("podaj mase:"), input('podaj wzrost:'), input('podaj plec:')]
  BMI=(float(dane[1])/(float(dane[2])**2))
  if "kobieta" in dane[3]:
    if BMI <16.5:
      print(dane[0], "anoreksja");
    elif 16.5 < BMI < 20:
      print(dane[0], 'niedowaga');
    elif 20 < BMI < 25:
      print(dane[0], "norma");
    elif 25 < BMI < 30:
      print(dane[0], "norma");
    else:
      print('otylosc');
  if "mezczyzna" in dane[3]:
    if BMI <18.5:
      print(dane[0], "anoreksja");
    elif 18.5 < BMI < 22.5:
      print(dane[0], 'niedowaga');
    elif 22.5 < BMI < 27.5:
      print(dane[0], "norma");
    elif 27.5 < BMI < 32.5:
      print(dane[0], "norma");
    else:
      print(dane[0], 'otylosc');
  pytanie=(input('tak czy nie'))

			 
