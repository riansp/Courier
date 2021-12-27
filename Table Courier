
print('Hai Beni')
print('Hari ini anda harus mengantarkan logistik harian ke restoran yang sudah ditentukan dengan' ' '     
      'jarak dan konsumsi bahan bakar yang   sudah ada, Berikut Tabel Informasinya:')
print('='*127)
#patokan untuk 1L dapat ditempuh sejauh 2.5KM

jr1 = 8
jr2 = 5.3
jr3 = 9.5
jr4 = 10
jr5 = 11
jr6 = 20.5
jr7 = 3.3
jr8 = 4.8
jr9 = 6.5
jrplg = (round(jr1 + jr2 + jr3 + jr4 + jr5 + jr6 + jr7 + jr8 + jr9, 2))
Total1 = (round(jrplg * 2, 5))

Resto1 = (round(jr1/2.5*1, 3))
Resto2 = (round(jr2/2.5*1, 3))
Resto3 = (round(jr3/2.5*1, 3))
Resto4 = (round(jr4/2.5*1, 3))
Resto5 = (round(jr5/2.5*1, 3))
Resto6 = (round(jr6/2.5*1, 3))
Resto7 = (round(jr7/2.5*1, 3))
Resto8 = (round(jr8/2.5*1, 3))
Resto9 = (round(jr9/2.5*1, 3))
Kantor = (round(jrplg/2.5*1, 3))
Total2 = (round(Total1/2.5*1, 2))

from prettytable import PrettyTable

tabelkurir = PrettyTable(["Nomor", "Tujuan Resto", "Jarak Tempuh/KM", "Konsumsi BBM/L"])
#addtabel
tabelkurir.add_row(["1", "Kantor Ke Restauran 1", jr1, Resto1])
tabelkurir.add_row(["3", "Restauran 2 ke Restauran 3", jr2, Resto2])
tabelkurir.add_row(["4", "Restauran 3 ke Restauran 4", jr3, Resto3])
tabelkurir.add_row(["5", "Restauran 4 ke Restauran 5", jr4, Resto4])
tabelkurir.add_row(["6", "Restauran 5 ke Restauran 6", jr5, Resto5])
tabelkurir.add_row(["7", "Restauran 6 ke Restauran 7", jr6, Resto6])
tabelkurir.add_row(["8", "Restauran 7 ke Restauran 8", jr7, Resto7])
tabelkurir.add_row(["9", "Restauran 8 ke Restauran 9", jr8, Resto8])
tabelkurir.add_row(["10", "Restauran 9 ke Restauran 10", jr9, Resto9])
tabelkurir.add_row(["11", "Arah Pulang Ke Kantor", jrplg, Kantor])
tabelkurir.add_row(["12", "Total Perjalanan Pergi Pulang", Total1, Total2])

print(tabelkurir)
print('='*127)
print('Tabel diatas merupakan jarak dan konsumsi BBM untuk melakukan pengiriman pada hari ini')
print('stay safe and be careful Beni')
