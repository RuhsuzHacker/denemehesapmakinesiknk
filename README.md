# Proje deneme
while ("true"):
    sozluk={"toplama:":1, "çıkarma:":2,"çarpma:":3,"bölme:":4}
    print(sozluk)
    a=int(input ("birinci sayıyı giriniz:"))
    b=int(input ("ikinci sayıyı giriniz:"))
    c=int(input ("işleminizi seçiniz"))

    if (c==1):
        sonuc=a+b
        print (sonuc)
    elif (c==2):
        sonuc=a-b
        print (sonuc)
    elif (c==3):
        sonuc=a*b
        print (sonuc)
    elif (c==4):
        sonuc=a/b
        print(sonuc)
    else:
        print("hatalı giriş...")
