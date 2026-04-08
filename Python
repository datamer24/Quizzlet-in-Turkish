def main():
    print(" 😎 Benimle bir Quiz'e Ne Dersin?! Endişelenme, 	☺️ Sen Yaparsın :) ")
    
    # Quiz soruları ve cevapları
    sorular = [
        {"soru": "1. Sorum: Türkiye'nin başkenti neresi?", "cevap": "Ankara"},
        {"soru": "2. Sorum: C++ bir programlama dili midir? (evet/hayır)", "cevap": "Evet"},
        {"soru": "101 + 20 hangi sayının karesidir?", "cevap": "11"},
        {"soru": "Dünyanın en küyük devleti hangisidir?", "cevap": "Vatikan Şehir Devleti (Stato della Città del Vaticano)"},
        {"soru": "Fransa'nın başkenti hangi neresidir? (evet/hayır)", "cevap": "Paris"}
    ]
    
    puan = 0

    for soru in sorular:
        cevap = input(soru["soru"] + " ").lower()  
        if cevap == soru["cevap"]:
            print("Doğru! ✅\n")
            puan += 1
        else:
            print("Yanlış! ❌ Doğru cevap:", soru["cevap"], "\n")

    print("Quizin sonuna geldik! Toplam puanın:", puan, " /", len(sorular))
    
    if puan == len(sorular):
        print("😍 Ay! Harika! Hem de çok Harika! Hepsini doğru cevapladın! ")
    elif puan >= len(sorular) // 2:
        print("Güüüzeeelll! 🤗")
    else:
        print("Daha iyi olacaksın, merak etme! 🧐✍️")
