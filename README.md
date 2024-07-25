# yas
yas
kripto_cuzdan/
├── README.md
├── .gitignore
├── wallet_generator.py
└── requirements.txt
# Kripto Cüzdan Adresi Oluşturucu

Bu proje, basit bir Python scripti kullanarak rastgele kripto cüzdan adresleri oluşturur.

## Kullanım

```bash
python wallet_generator.py
__pycache__/
*.pyc
import random
import string

def generate_wallet_address(length=34):
    chars = string.ascii_letters + string.digits
    wallet_address = ''.join(random.choice(chars) for _ in range(length))
    return wallet_address

if __name__ == "__main__":
    print("Yeni Kripto Cüzdan Adresi: ", generate_wallet_address())
# Bu proje için özel bir gereksinim yok
pip install -r requirements.txt
python wallet_generator.py

