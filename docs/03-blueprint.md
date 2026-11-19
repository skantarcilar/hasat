# 03 | Master Blueprint
## Kuruluş ilkeleri
Üreten, taşıyan, alan ve hizmet veren kazanır. Ölçülebilir değer; açık hizmet ücretleri, gönüllü katılım, rekabetçi çoklu partner, ürün mülkiyeti ve finans riski mümkün olduğunca Hasat dışında. Kendi kamyon/depo/kantar filosu yok; güvenlik ve mevzuat pazarlık konusu değil. Taahhüt öncesi açık koşullar; mağduriyette tek koordinasyon muhatabı, fakat sınırsız zarar garantisi yok.

## Roller ve ürün kapsamı
Üretici: parsel/ürün/parti, hazır ve planlı arz, sözleşme, net hakediş, girdi/finans. Alıcı: spot, talep, haftalık düzenli, birleşik tedarik; kalite ve kullanım amacı, teslim penceresi. Taşıyıcı: araç özelliği/yetki/kapasite, şehir ve rota, tek/tekrarlı ileri tarihli sefer ve boş dönüş; bekleme ve net kazanç. Toplayıcı/point: köy, toplama, tartım, tasnif, muhafaza, ekipman, randevu. İş gücü: yetkili ve sigortalı partner, kapasite. Uzman: bağımsız kalite/kontrol/danışmanlık; ilaç komisyonu yok. Banka/sigorta: bağımsız değerlendirme, teklif, teminat, limit/kapsam ve vade doğrulaması. Girdi bayisi: uygun ürün, yerel/ulusal teklif, stok, toplu alım, teslim. Zirai ilaç internet satışı/tanıtımı kapsam dışı; mevzuata uygun danışmanlığa bakılacak.

## Core
Identity (KYC/KYB, yetki, cihaz/belge); Zones (il, ilçe, yol mesafesi, rota, hizmet bölgesi); Planner (tahmini/tekrarlı plan, slot); Optimizer (maliyet, ağırlık/hacim/dingil, zaman, uygunluk, minimum marj ve yedek); Lock (tahsis ve çift rezervasyon önleme); Assurance (banka onaylı ödeme/performans/avans güvencesi, poliçe); Flow (ETA ve bağımlılık); Measure (ticari uygun ve muayeneli tartı, dara, parti); Quality (ürün kullanım amacı, numune, izlenebilirlik/geri çağırma); Recovery (yeniden planlama, alternatif satış, reddedilen ürün); Trust (rol bazlı gerçek işlem performansı, itiraz); Ledger (kanıt ve olay kaydı); Settlement (kısmi kabul ve hakediş, mutabakat); Compliance (HKS/GİB/taşımacılık/gıda/rekabet/KVKK); Control Tower (istisna kuyruğu).
Ticari modüller: Trade, Move, Finance, Insurance, Input/Fuel, Work, Expert, Points, Intelligence. Tek kimlik ve role göre ana ekran; sesli taslak, düşük bağlantı, offline delil senkronizasyonu; kurumsal talepler CSV/ERP. Finans, sigorta, girdi, uzman modülleri ardışık doğrulama ile açılır.

## Uçtan uca
1. Kimlik ve rol doğrula; bölge, kalite, tarih, kapasite, fiyat veya fiyat formülü seç.
2. Tahmini arz/talep ve hizmet takvimi oluştur; eşleştirme ve gerçek teslim maliyeti sun; hızlı/esnek/düzenli seçenek.
3. Geçici rezervasyon (TTL); karşılıklı teklif onayı; fiyat, tolerans, kabul, mülkiyet/risk/muhafaza ayrımı, sorumluluk, bekleme, iptal, mücbir sebep ve ödeme koşulları.
4. Gerekli yetkili teminat/poliçe/doğrulama, kalite ve taşıma uygunluğu; tüm bağımlılıkları kilitle. Kısmi failure rezervasyonları serbest bırak.
5. Hazırlık, kantar, parti kodu, yükleme, sevkiyat; her el değiştirmede teslim kanıtı; ETA ve sıcaklık gerektiğinde.
6. Varış; onaylı ölçüm, kısmi kabul/ret, yeniden tartım, fotoğraf, bağımsız inceleme; ihtilafsız tutarlar bekletilmez.
7. Yetkili partner üzerinden ödeme; mutabakat, teminat serbest bırakma, işlem değerlendirmesi ve kalite geri beslemesi.

## İstisnalar
Üretici eksik/kalitesiz: alternatif parti, onay veya kısmi teslim. Alıcı iptal/ret: koşullara göre maliyet, güvenli alternatif alıcı veya iade. Araç arızası: yedek, rota, küçük araç; kapasite ve maliyet onayı. Gecikme: ETA etkisini hesapla, bildirim, tolerans ve bekleme bedeli, gerektiğinde yeniden planla. Tartım farkı: ölçüm belirsizliği, dara ve doğal kayıp ayrı; bağımsız yeniden tartım. Banka/ödeme kesintisi: yeni lock durdur, ödeme tekrarını engelle, mutabakat; manuel yükümlülük atlama yok. Güvensiz gıda: karantina/geri çağırma; yeniden satış yok. Afet: bölgesel stop, öncelik. Hasat hatası: kendi sözleşmesel sorumluluğu. 

