# set
print("============selamat datang di kalimat irisan===============") 
print(" 1. elemen yang sama") 
print(" 2. elemen yang beda") 
pilihan =int(input("masukkan pilihan anda")) 
kalimat = input("masukkan kalimat pertama") 
kalimat2 = input("masukkan kalimat kedua") 
print (type(kalimat)) 
kalimat = set(kalimat) 
kalimat2 = set(kalimat2) 
irisan = kalimat & kalimat2 
irisan2 = kalimat ^ kalimat2 
jumlah = len(irisan) 
jumlah2 = len(irisan2) 
if pilihan == 1:     
  print("elemen yang sama adalah",irisan)     
  print("jumlah elemen yang sama",jumlah) 
elif pilihan == 2:     
  print("elemen yang beda adalah",irisan2)    
  print("jumlah elemen yang beda",jumlah2) print(type(kalimat))
