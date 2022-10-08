total_belanja = int(input("Masukan total belanja : Rp. "))

if total_belanja >= 15000000 and total_belanja < 25000000:
    diskon = total_belanja * (10/100)
elif total_belanja >= 25000000 and total_belanja < 35000000:
    diskon = total_belanja * (12.5/100)
elif total_belanja >= 35000000 and total_belanja < 60000000:
    diskon = total_belanja * (15/100)
elif total_belanja >= 60000000:
    diskon = total_belanja * (20/100)
else:
    pass
   
total_bayar = total_belanja - diskon
print ("Mendapatkan diskon harga sebesar Rp.",(int(diskon)))
print ("Total yang harus dibayar adalah : Rp.",(int(total_bayar)))

uang_diberikan = int(input("Uang diberikan adalah : Rp."))


kembalian = uang_diberikan - total_bayar
print ("Kembalian anda adalah : Rp.",(int(kembalian)))

print("======= Menampilkan pecahan =======")

uang = kembalian
uang_pecahan = [100000, 50000, 20000, 10000, 5000, 2000, 1000, 500, 200, 100]
jumlah_pecahan = {}
sisa = uang
print('Kembaliannya adalah Rp.{},  \Pecahan yang kita butuhkan yaitu: '.format(int(uang)))
for pecahan in uang_pecahan:
    if sisa < pecahan:
        continue
    banyak_pecahan = int(sisa / pecahan)
    sisa = sisa - ( pecahan * banyak_pecahan )
    print('pecahan {} : {}'.format(pecahan, banyak_pecahan))
