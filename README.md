print("1.Toplama")
print("2.Çıkarma")
print("3.Çarpma")
print("4.Bölme")
print("5.Sayının üssüsünü alma")

choice= input("Seçiminiz")

match choice:
    case "1":
        num1=float(input("Birinci sayiyi giriniz: "))
        num2=float(input("İkinci sayiyi giriniz: "))
        result=num1+num2
        print(f"{num1} + {num2} = {result}")
    case "2":
        num1=float(input("Birinci sayiyi giriniz: "))
        num2=float(input("İkinci sayiyi giriniz: "))
        result=num1-num2
        print(f"{num1} - {num2} = {result}")
    case "3":
        num1=float(input("Birinci sayiyi giriniz: "))
        num2=float(input("İkinci sayiyi giriniz: "))
        result=num1*num2
        print(f"{num1} * {num2} = {result}")
    case "4":
        num1=float(input("Birinci sayiyi giriniz: "))
        num2=float(input("İkinci sayiyi giriniz: "))
        result=num1/num2
        print(f"{num1} / {num2} = {result}")
    case "5":
        num1=float(input("Birinci sayiyi giriniz: "))
        num2=float(input("İkinci sayiyi giriniz: "))
        result=num1**num2
        print(f"{num1} ** {num2} = {result}")
