sozluk = {
            "CRINGE": "Garip ya da utandırıcı bir şey",
            "LOL": "Gülerek dalga geçmek",
            "GG": "Oyunu kaybetmek",
            "LMAO": "Abartarak gülmek",
            "BOOMER": "Aşağılanan kimse",
            "MİSSLEMEK": "Kaçırmak",
}
word = input("Anlamadığınız bir kelime yazın (hepsi büyük harfle):")

if word in sozluk.keys():
    print(sozluk[word])

else:
    print("Bu sözcük sözlükte yok.")
