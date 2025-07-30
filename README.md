# TurkishNameWordlist

Bu proje, **Türkçe isimlerden** (adlardan) oluşan bir kelime listesini içerir.

## 📄 İçerik

- `names.txt`: Türkçe adların bulunduğu düz metin dosyası. Her satırda bir isim olacak şekilde düzenlenmiştir.

## 💡 Kullanım Alanları

- Wordlist tabanlı güvenlik testleri (brute-force, dictionary attack vb.)
- Sosyal mühendislik analizleri
- Doğal dil işleme (NLP) projeleri
- Sahte veri (mock data) üretimi
- Veri temizleme veya isim kontrolü işlemleri

## 🧪 Örnek Kullanım

```bash
# İlk 10 ismi görüntüle
head names.txt

# Belirli bir harf ile başlayan isimleri filtrele (örneğin A ile başlayanlar)
grep '^A' names.txt
