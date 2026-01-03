# ⚠️ DISCLAIMER  
Project ini dibuat untuk **tujuan eksperimen**.  
Bukan untuk spam atau penyalahgunaan layanan email.

---

## 🚀 Fitur
- 📬 Email sender berbasis **Python**
- 🎨 Tampilan terminal **pretty & berwarna**
- 📊 Progress bar + ETA real-time
- 🔐 Login Gmail SMTP (TLS)
- 📧 Opsi:
  - Email default
  - Email Gmail sendiri
- 🧪 Test koneksi & autentikasi otomatis
- 📝 Log pengiriman (`pretty_send.log`)
- ⛔ Konfirmasi sebelum kirim massal
- 🛑 Bisa dihentikan kapan saja (Ctrl + C)

---

## 📸 Screenshots
![alt text](https://github.com/Tenkxzz/spam-gmail/blob/main/images/main_menu.jpg?raw=true)

---

## ⚠️ Catatan
- Gunakan **Password pribadi**
- Jangan membagikan password Gmail
- Disarankan memakai **Gmail App Password**
- Patuhi kebijakan Google (SMTP & Email)
- Gunakan tools secara **bertanggung jawab**

---

## 👤 Author
- Nama: **Tenz**
- Jenis Project: **Spam Email**
- Tujuan: **Eksperimen**

---

## 🔥 Join Community
Gabung ke channel WhatsApp untuk:
- Update project & fitur baru
- Share tools Termux & Python
- Diskusi santai

📱 https://tinyurl.com/2cxmlqtl  

> Channel ini bersifat komunitas, bukan layanan resmi.

---

## 🚀 Instalasi (Termux)

```bash
pkg update

pkg upgrade

pkg install python

pkg install python-cryptography -y

pkg install clang make openssl libffi

pip install pycryptodome

pkg install git

git clone https://github.com/Tenkxzz/spam-gmail.git

cd spam-gmail

pip install requests colorama

python main.py
