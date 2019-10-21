# Mengenal apa itu operator

-	Operator adalah simbol khusus pada Python yang melakukan perhitungan aritmatika dan logika.
-	Nilai yang dihasilkan operator disebut operand

## Lab 2

## Di lab 2 ini kita akan mencoba mengoperasikan operator, contoh:
1.	a=input("masukkan nilai a: ")
2.	b=input("masukkan nilai b: ")
Langkah 1 dan 2 nanti akan meminta kita untuk memasukkan nilai kepada variabel a dan b.
3.	print("variable a= ", a)
4.	print("variable b= ", b)
Di langkah 3 dan 4 ini akan menuliskan kembali nilai yang telah kita masukkan di langkah 1 dan 2 tadi.
5.	print("hasil penggabungan {1}&{0}=%d".format (a,b) %(a+b))
Langkah 5 akan menggabungkan nilai variable a dan b, tapi pada tahap ini akan terjadi error karena tipe data pada variable adalah string, sedangkan yang diminta adalah nomor atau integer, maka kita harus mengubah '%d' menjadi '%s' agar sistem membacanya sebagai string bukan integer.
Lalu karena {1} adalah variable b dan {0} adalah variable a (b,a), maka harus diubah menjadi {0}&{1} agar tidak terbalik dan sesuai dengan format yang akan digabungkan.
6.	a=int(a)
7.	b=int(b)
Di langkah 6 dan 7 ini akan mengkonversikan data variable a dan b, dari yang tadinya str menjadi int.
8.	print("hasil penjumlahan {0}&{1}=%d".format(a,b) %(a+b))
Langkah 8 akan menjumlahkan nilai variable a dan b.
9.	print("hasil pembagian {0}&{1}=%d".format(a,b) %(a/b))
Langkah 9 akan membagi nilai variable a dan b.
Tips : Gunakan '%f' atau '%s' bila hasil pembagiannya adalah angka desimal.
