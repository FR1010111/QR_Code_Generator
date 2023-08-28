# QR_Code_Generator
# it's the shorter format of generating QR Code using Python
import qrcode
generate_image = qrcode.make("https://www.youtube.com/watch?v=1cCDfDIjp1Q")
generate_image.save('Sigma.png')
