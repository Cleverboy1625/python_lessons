# python_lessons
python homework
# #2-lesson
# print('Assalom alaykum')
# #print(Hayrli tong!)#xato qaytaradi tirnoq
# #ichida yozilmagan
# print(2+4*2)
# print(19/5)
# print(2**4)
# 3- lesson
# # Quyidagi matnni aynan shunday ko'rinishda konsolda chiqaring:
# # "Nexia", "Tico", 'Damas' ko'rganlar qilar havas
# print("\"Nexia\", \"Tico\", 'Damas' ko'rganlar qilar havas")# \ bu belgi har qanday maxsus belgi oldidan ishlatiladi
# # Quyidagi misollarga yechimni Pythonda chiqaring. Har bir misoldan avval misol matnini izoh ko'rinishida yozing:
# # 5 ning 4-darajasini toping
# print(" 5 ning 4-darajasi  ",5**4, "ga teng")
# # 22 ni 4 ga bo'lganda qancha qoldiq qoladi?
# print(" 22 ni 4 ga bo'lganda qoldiq " ,22%4, "ga teng")
# # Tomonlari 125 ga teng kvadratning yuzi va perimetrini toping
# a=125
# s=a*a# yoki(or) s=a**2
# p=4*a
# print("Tomonlari 125 ga teng kvadratning yuzi",s, "va perimetri", p)
# # Diametri 12 ga teng bo'lgan doiraning yuzini toping  ( deb oling)
# d=12
# pi=3.14
# s=pi*d**2/4
# print("Diametri 12 ga teng bo'lgan doiraning yuzi",s)
# Katetlari 6 va 7 bo'lgan to'g'ri burchakli uchburchakning gipotenuzasini toping (Pifagor teoremasidan foydalaning)
# a=6
# b=7
# print("Katetlari 6 va 7 bo'lgan to'g'ri burchakli uchburchakning gipotenuzasi",(6**2+7**2)**0.5)
# 4-lesson
# # "Hello World!" matnini yangi o'zgaruvchiga yuklang va print() yordamida konsolga chiqaring
# salom='hello world'
# # xabar deb nomlangan o'zgaruvchiga biror matn yuklang va konsolga chiqaring, keyin esa o'zgaruvchiga yangi qiymat berib uni ham konsolga chiqaring.
# xabar="cleverboy"
# #print(xabar)
# xabar="oyatillo"
# #print(xabar)
# # class den nomlangan o'zgaruvchi yarating, unga biror qiymat bering va konsolga chiqaring (siz kutgan natija chiqdimi?)
# #class="salom"
# #print(class)# bu python key words ichida bor va o'zgaruvchi bo'lmedi
# # Quyidagi kodni bajaring:
# radius = 5
# pi = 3.14159
# aylana_yuzi = pi * radius**2
# print("Radiusi" , radius, "ga teng aylananing yuzi=", aylana_yuzi)
#5-lesson
#Quyidagi o'zgaruvchilarni yarating:
kocha = "Bog'bon"
mahalla = "Sog'bon"
tuman = "Bodomzor"
viloyat = "Samarqand"
#Yuqoridagi o'zgaruvchilarni jamlab, quyidagi ko'rinishda konsolga chiqaring:
#Bog'bon ko'chasi, Sog'bon mahallasi, Bodomzor tumani, Samarqand viloyati
# print(kocha,"ko'chasi",mahalla, 'mahallasi', tuman ,'tumani',viloyat,'viloyati')
# Yuqoridagi o'zgaruvchilarning (kocha, mahalla, tuman, viloyat) qiymatini foydalanuvchidan so'rang. Va avvalgi mashqni takrorlang.
#kocha, mahalla, tuman, viloyat=map(str, input().split())
#map() funktsiyasi bir nechta o'garuvchini qabul qilishga mo'ljallangan
#split() metodi esa o'zgaruvchilarni ajiratib beradi (...) qavs ichida nimadan foydalansak o'zgaruvchilarni ajiratishda shundan foydalanamiz
# print(kocha,"ko'chasi",mahalla, 'mahallasi', tuman ,'tumani',viloyat,'viloyati')
# Yuqoridagi matnni konsolga chiqarishda har bir verguldan keyin yangi qatordan yozing
# print(kocha+" ko'chasi,\n"+mahalla, ' mahallasi\n'+tuman +' tumani,\n'+viloyat+' viloyati')
# Yuqoridagi matnni f-string yordamida, yangi, manzil deb nomlangan o'zgaruvchiga yuklang
manzil = f"{kocha} ko'chasi, {mahalla} mahallasi, {tuman} tumani, {viloyat} viloyati"
#print(manzil)
# manzilga biz yuqorida o'rgangan title(), upper(), lower() , capitalize() metodlarini qo'llab ko'ring.
# print(kocha.capitalize()+" ko'chasi,\n"+mahalla.title(), ' mahallasi\n'+tuman.upper() +' tumani,\n'+viloyat.lower()+' viloyati')
#6-lesson
#Foydalanuvchi kiritgan sonning kvadrati va kubini konsolga chiqaruvchi dastur
#a = int(input("Istalgan son kiriting ="))
#print("sonning kvadrati=",a**2,'kubi=',a**3)
#Foydalanuvchining yoshini so'rab, uning tug'ilgan yilini hisoblab, konsolga chiqaruvchi dastur
#age=int(input('yoshingiz nechchida: \n >>>'))
#print(2023-age,"- yilda tug'ilgansiz")
#Foydalanuvchidan ikki son kiritshni so'rab, kiritilgan sonlarning yig'indisi, ayirmasi, ko'paytmasi va bo'linmasini chiqaruvchi dastur
#a,b=map(int,input().split())
#print("yig'indi=" , a+b,"ayirma=",a-b,"ko'paytma=",a*b,"bo'linma=",a/b,"int value=",a//b,"rest=",a%b,"garduete=",a**b)
#7-lesson
#ismlar degan ro'yxat yarating va kamida 3 ta yaqin do'stingizning ismini kiriting
friends = ['ali', 'cleverboy', "go'zalina"]
#Ro'yxatdagi har bir do'stingizga qisqa xabar yozib konsolga chiqaring:
# print("salom mening do'stim ",friends[0].title())
# oshna=friends[1].title()
# print("assalomu alaykum !",oshna)
# print("Vazifalar qale :) ",friends[2].title())
#sonlar deb nomlangan ro'yxat yarating va ichiga turli sonlarni yuklang (musbat, manfiy, butun, o'nlik).
numbers = [1, 11, 1.7, -1.2, -7]
#Yuqoridagi ro'yxatdagi sonlar ustida turli arifmetik amallar bajarib ko'ring.
#print(numbers[1]+numbers[-2],numbers[0]*numbers[3])
#Ro'yxatdagi ba'zi sonlarning qiymatini o'zgartiring, ba'zilarini esa almashtiring
# numbers.remove(11)
# numbers[1] = 55
# numbers[2] = numbers[-1] - (-23)
# del numbers[-3]
# #print(numbers)
# #t_shaxslarva z_shaxslar degan 2 ta ro'yxat yarating va biriga o'zingiz eng ko'p hurmat qilgan tarixiy shaxslarning, ikkinchisiga esa zamonamizdagi tirik bo'lgan shaxslarning ismini kiriting.
# t_shaxslar=["Z.M.Bobur","A.Navoiy",'Amir Temur']
# z_shaxslar=["Clever boy","Baby","Oyatillo"]
# #Yuqoridagi ro'yxatlarning har biridan bittadan qiymatni sug'urib olib (.pop()), quyidagi ko'rinishda chiqaring:
# #print(f" Assalomu alaykum {t_shaxslar.pop(2)} mening ismim {z_shaxslar.pop(0)}")
# #friendsnomli bo'sh ro'yxat tuzing va unga .append() yordamida 5-6 ta mehmonga chaqirmoqchi bo'lgan do'stlaringizni kiriting.
# friends=[]
# friends.append("Ali")
# friends.append("Clever boy")
# friends.append("baby")
# friends.append("go'zalina")
# friends.append("jo'ker")
# #print(friends)
# #Yuqoridagi ro'yxatdan mehmonga kela olmaydigan odamlarni .remove() metodi yordamida o'chrib tashlang.
# friends.remove("Ali")
# friends.remove("jo'ker")
# #Ro'yxatning oxiriga, boshiga va o'rtasiga yangi ismlar qo'shing.
# friends.append('oybola')
# friends.insert(-1, 'dobbiy')
# friends.insert(3, 'Oyatillo')
# #print(friends)
# #Yangi mehmonlar deb nomlangan bo'sh ro'yxat yarating. .pop() va .append() metodlari yordamida mehmonga kelgan do'stlaringizning ismini friends ro'yxatidan sug'urib olib, mehmonlar ro'yxatiga qo'shing.
# mehmonlar = []
# mehmonlar.append(friends[1])
# mehmonlar.append(friends.pop(2))
# mehmonlar.append(friends.pop(-1))
# print("Kelgan mehmonlar>>> ", mehmonlar)
# #8-lesson
# #O'zingizga ma'lum davlatlarning ro'yxatini tuzing va ro'yxatni konsolga chiqaring
# davlatlar = ["O'zbekiston", "Rossiya" ,"Qozog'iston",  "Xitoy", "AQSh"]
# print(davlatlar)
# #Ro'yxatning uzunligini konsolga chiqaring
# print(len(davlatlar))
# #sorted() funktsiyasi yordamida ro'yxatni tartiblangan holda konsolga chiqaring
# print(sorted(davlatlar))

# #sorted() yordamida ro'yxatni teskari tartibda konsolga chiqaring
# print(sorted(davlatlar, reverse=True))

# #Asl ro'yxatni qaytadan konsolga chiqaring
# print(davlatlar)

# #reverse() metodi yordamida ro'yxatni ortidan boshlab chiqaring
# davlatlar.reverse()
# print(davlatlar)

# #sort() metodi yordamida ro'yxatni avval alifbo bo'yicha, keyin esa alifboga teskari tartibda konsolga chiqaring.
# davlatlar.sort()
# print(davlatlar)
# davlatlar.sort(reverse=True)
# print(davlatlar)

# #120 dan 1200 gacha bo'lgan juft sonlar ro'yxatini tuzing
# sonlar = list(range(120,1200,2))

# #Ro'yxatdagi sonlar yig'indisini hisoblang va konsolga chiqaring
# print(sum(sonlar))

# #Ro'yxatdagi eng katta va eng kichik son o'rtasidagi ayirmani hisoblang va konsolga chiqaring
# print(max(sonlar)-min(sonlar))

# #Ro'yxatdagi elementlar sonini hisoblang
# print(len(sonlar))

# #Ro'yxatning boshidan, o'rtasidan va oxiridan 20 ta qiymatni konsolga chiqaring
# print(sonlar[:20])
# print(sonlar[-20:])
# print(sonlar[530:550])

# #taomlar degan ro'yxat yarating va ichiga istalgan 5ta taomni kiriting
# taomlar = ['osh','somsa','manti','shashlik','non']

# #nonushta degan yangi ro'yxatga taomlardan nusxa oling
# nonushta = taomlar[:]

# #Yangi ro'yxatda faqat nonushtaga yeyiladigan taomlarni qoldiring, va qo'shimcha 2 ta taom qo'shing
# nonushta.remove('non')
# nonushta.remove('shashlik')
# nonushta.remove('manti')
# nonushta.append('somsa')
# nonushta.append('shirinlik')

# #Ikkala ro'yxatni ham (taomlar va nonushta) konsolga chiqaring
# print(taomlar)
# print(nonushta)

# #Yuqoridagi nonushta ro'yxatini o'zgarmas ro'yxatga aylantiring va nonushta[0] = "qaymoq va non" deb qiymat berib ko'ring.
# nonushta = tuple(nonushta)
# nonushta[0] = "qaymoq va non"

#9-lesson

#Kamida 5 elementdan iborat ismlar degan ro'yxat tuzing, va ro'yxatdagi har bir ismga takrorlanuvchi xabar yozing

# friends=['ali','cleverboy',"go'zalina","baby","jo'ker"]
# for ism in friends:
#   print("Assalommu alaykum" , ism)
#Yuoqirdagi tsikl tugaganidan so'ng, ekranga "Kod n marta takrorlandi" degan xabarni chiqaring (n o'rniga kod necha marta takrorlanganini yozing)
#print(f" kod {len(friends)} martta takrorlandi " )
#10 dan 100 gacha bo'lgan toq sonlar ro'yxatini tuzing. Ro'yxatning xar bir elementining kubini yangi qatordan konsolga chiqaring.
# for son in range(9,100,2):
#   print(son**3)
#Foydalanuvchidan 5 ta eng sevimli kinolarini kiritshni so'rang, va kinolar degan ro'yxatga saqlab oling. Natijani konsolga chiqaring.
# movie=["Harry potter","joker","qasoskorlar","veronika"]
# #print(movie)
# suhbat=[]
# son = int(input("bugun nech kishi bn uchrashdiz ? "))
# n=1
# for i in range(1,son+1):
#   a=suhbat.append(input(f"{n} kim bn ko'rishdiz>>> "))
#   n+=1
# print(suhbat)
#10-lesson
# #Yangi cars = ['toyota', 'mazda', 'hyundai', 'gm', 'kia'] degan ro'yxat tuzing, ro'yxat elementlarining birinchi harfini katta qilib konsolga chqaring. GM uchun ikkala harfni katta qiling.
# cars = ['toyota', 'mazda', 'hyundai', 'gm', 'kia']
# for car in cars:
#   if car == 'gm':
#     print(car.upper())
#   else:
#     print(car.title())

# #Yuqoridagi mashqni teng emas (!=) operatori yordamida bajaring.
# cars = ['toyota', 'mazda', 'hyundai', 'gm', 'kia']
# for car in cars:
#   if car != 'gm':
#     print(car.title())
#   else:
#     print(car.upper())

# #Foydalanuvchi login ismini so'rang. Agar login admin bo'lsa, "Xush kelibsiz, Admin. Foydalanuvchilar ro'yxatini ko'rasizmi?" xabarini konsolga chiqaring. Aks xolda, "Xush kelibsiz, {foydalanuvchi_ismi}!" matnini konsolga chiqaring.
# login = input("Login kiriting: ")
# if login.lower() == 'admin':
#   print("Xush kelibsiz Admin, foydalanuvchilar ro'yxatini ko'rasizmi?")
# else:
#   print(f"Xush kelibsiz {login.title()}!")

# #Foydalanuvchidan 2 ta son kiritishni so'rang. Agar ikki son bir-biriga teng bo'lsa, "Sonlar teng" ekan degan yozuvni konsolga chiqaring.
# a, b = map(float, input().split())
# if a == b: print(f"Sonlar teng: {a}={b}")

# #Foydalanuvchidan istalgan son kiritishni so'rang. Agar son manfiy bo'lsa konsolga "Manfiy son", agar musbat bo'lsa "Musbat son" degan xabarni chiqaring.
# son = float(input("Istalgan son kiriting:"))
# print("Son manfiy") if son < 0 else print("Son musbat")

# #Foydalanuvchidan son kiritishni so'rang, agar son musbat bo'lsa uning ildizini hisoblab konsolga chiqaring. Agar son manfiy bo'lsa, "Musbat son kiriting" degan xabarni chiqaring.
# son = float(input('Istalgan son kiriting: '))
# print(son**(1 / 2)) if son > 0 else print('Musbat son kiriting')
