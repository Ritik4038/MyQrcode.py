# MyQrcode.py
import qrcode

img = qrcode.make("https://github.com/Ritik4038")

img.save("myQR.jpg")
