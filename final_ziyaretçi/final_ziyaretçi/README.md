


Bu proje, kurumlara gelen ziyaretçilerin giriş-çıkış bilgilerini ve randevularını kaydetmek için geliştirilmiş bir web uygulamasıdır. Flask framework’ü ile yazılmıştır.


- Ziyaretçi giriş/çıkış kaydı
- Randevu alma ve listeleme
- Kullanıcı yönetimi
- Ziyaretçi filtreleme ve raporlama
- JSON dosyaları ile veri yönetimi
- SQLite veritabanı desteği



```
ziyaretçi dosyası yeni/
│
├── app.py                  # Ana Flask uygulaması
├── db2json.py, db3json.py  # Veritabanını JSON'a çeviren yardımcı betikler
├── instance/ziyaret.db     # SQLite veritabanı
├── templates/              # HTML sayfa şablonları (Jinja2)
│   ├── anasayfa.html
│   ├── giris.html
│   ├── kayit.html
│   ├── randevu.html
│   └── ...
├── users.json              # Kullanıcı verileri
├── ziyaretciler.json       # Ziyaretçi verileri
├── requirements.txt        # Gerekli Python paketleri
└── README.md               # Proje açıklama dosyası
```


1. Gerekli paketleri yükleyin:
   ```bash
   pip install -r requirements.txt
   ```

2. Flask uygulamasını başlatın:
   ```bash
   python app.py
   ```

3. Tarayıcınızda aşağıdaki adresi açın:
   ```
   http://127.0.0.1:5000/
   ```


- Python 3.7+
- Flask
- Werkzeug, Jinja2, vb. (requirements.txt içinde)


