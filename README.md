print("Hoşgeldiniz. Not ortalamanızı hesaplamak için sizden bir takım bilgiler istenecektir. Lütfen bekleyiniz...")
print("Öncelikle dersinize ait sözlü notu veriliyor ise lütfen 1'e, sözlü notu verilmiyor ise lütfen 2'ye basınız...")
sözlü = float(input())
if sözlü ==1:
    print("Hesaplamalara sözlü notu dahil edilmiştir.")
    print("2 Sınavdan oluşuyor ise lütfen 1'e basınız")
    print("3 Sınavdan oluşuyor ise lütfen 2'ye basınız")
    sinavSayisi = float(input())
    if sinavSayisi == 1:
        print("Notlarınızın hesaplanması için lütfen 1. sınav notunuzu giriniz...")
        not1 = float(input())
        print("Notlarınızın hesaplanması için lütfen 2. sınav notunuzu giriniz...")
        not2 = float(input())
        print("Lütfen sözlü notunuzu giriniz")
        snot = float(input())
        ort = (not1 + not2+snot) / 3
        print("Notlarınız alınmıştır. Ortalamanız hesaplanıyor. Lütfen bekleyiniz...")
        print("Ortalamanız:")
        print(ort)
    else:
        if sinavSayisi == 2:
            print("Notlarınızın hesaplanması için lütfen 1. sınav notunuzu giriniz...")
            not1 = float(input())
            print("Notlarınızın hesaplanması için lütfen 2. sınav notunuzu giriniz...")
            not2 = float(input())
            print("Notlarınızın hesaplanması için lütfen 3. sınav notunuzu giriniz...")
            not3 = float(input())
            print("Lütfen sözlü notunuzu giriniz")
            snot = float(input())
            ort = (not1 + not2 + not3+snot) / 4
            print("Notlarınız alınmıştır. Ortalamanız hesaplanıyor. Lütfen bekleyiniz...")
            print("Ortalamanız:")
            print(ort)
        else:
            print("Sistem dışında bir tercih yaptınız. Lütfen programı yeniden çalıştırınız")
            pass
else:
    if sözlü ==2:
        print("Hesaplamalara sözlü notu dahil edilmemiştir.")
        print("2 Sınavdan oluşuyor ise lütfen 1'e basınız")
        print("3 Sınavdan oluşuyor ise lütfen 2'ye basınız")
        sinavSayisi = float(input())
        if sinavSayisi == 1:
            print("Notlarınızın hesaplanması için lütfen 1. sınav notunuzu giriniz...")
            not1 = float(input())
            print("Notlarınızın hesaplanması için lütfen 2. sınav notunuzu giriniz...")
            not2 = float(input())
            ort = (not1 + not2) / 2
            print("Notlarınız alınmıştır. Ortalamanız hesaplanıyor. Lütfen bekleyiniz...")
            print("Ortalamanız:")
            print(ort)
        else:
            if sinavSayisi == 2:
                print("Notlarınızın hesaplanması için lütfen 1. sınav notunuzu giriniz...")
                not1 = float(input())
                print("Notlarınızın hesaplanması için lütfen 2. sınav notunuzu giriniz...")
                not2 = float(input())
                print("Notlarınızın hesaplanması için lütfen 3. sınav notunuzu giriniz...")
                not3 = float(input())
                ort = (not1 + not2 + not3) / 3
                print("Notlarınız alınmıştır. Ortalamanız hesaplanıyor. Lütfen bekleyiniz...")
                print("Ortalamanız:")
                print(ort)
            else:
                print("Sistem dışında bir tercih yaptınız. Lütfen programı yeniden çalıştırınız")
                pass
    else:
        print("Sistem dışında bir tercih yaptınız. Lütfen programı yeniden çalıştırınız")
        pass
