# Büyük Şirketlerde Departmanlar ve Rutin İşler

Bu doküman, VeriShift için potansiyel otomasyon alanlarını çıkarmak amacıyla hazırlanmıştır. Aşağıdaki görevlerin tamamı her şirkette aynı değildir; süreçler sektör, mevzuat, kullanılan ERP/CRM sistemleri ve şirket politikasına göre değişir.

## İnsan Kaynakları

- Personel ana verilerinin güncellenmesi
- Puantaj ve devam verilerinin kontrolü
- Bordro öncesi veri hazırlığı
- Yan hak listelerinin güncellenmesi
- İzin ve devamsızlık raporları
- SGK / İŞKUR için gerekli veri ve rapor hazırlıkları
- İşe giriş / çıkış kontrol listeleri
- Eğitim katılım raporları
- Performans değerlendirme raporları
- Norm kadro ve çalışan sayısı raporları

## Muhasebe ve Finans

- Gelen faturaların kontrolü ve sisteme aktarılması
- Cari hesap mutabakatları
- Banka hareketlerinin kontrolü
- Masraf fişi ve gider kayıtlarının işlenmesi
- Tahsilat / ödeme listelerinin hazırlanması
- Ay sonu kapanış kontrol listeleri
- Bütçe / gerçekleşen raporları
- Nakit akış raporları
- Yönetim finans raporları

## Vergi

- Beyanname öncesi veri toplama ve kontrol
- Dönemsel vergi raporları
- Vergi takvimi takibi
- Eksik belge / veri kontrolü
- Farklı sistemlerden vergiye esas verilerin konsolidasyonu

## Satınalma

- Teklif toplama ve karşılaştırma tabloları
- Tedarikçi performans raporları
- Sipariş / teslimat takibi
- Sözleşme bitiş tarihi takibi
- Fiyat değişim raporları
- Açık sipariş listeleri
- Satınalma bütçesi / gerçekleşen takibi

## İdari İşler / Tesis Yönetimi

- Servis, yemek, güvenlik, temizlik gibi hizmetlerin günlük / aylık kontrol raporları
- Tedarikçi SLA ve hizmet seviyesi takibi
- Arıza ve bakım kayıtlarının raporlanması
- Periyodik bakım takvimleri
- Sayaç ve enerji tüketim raporları
- Demirbaş ve envanter listeleri
- Araç filosu, yakıt ve bakım raporları
- Ziyaretçi ve erişim raporları
- Ofis tüketim malzemesi stok takibi

## Pazarlama

- Kampanya performans raporları
- Kanal bazlı bütçe / harcama raporları
- Lead raporları
- Sosyal medya performans özetleri
- Web analitik raporları
- Rakip ve fiyat takibi
- CRM verilerinin raporlanması

## Satış

- Günlük / haftalık satış raporları
- Pipeline ve fırsat raporları
- Teklif durum takibi
- Müşteri ziyaret / aktivite raporları
- Satış hedefi / gerçekleşen analizi
- Tahmin (forecast) raporları
- Müşteri yenileme / sözleşme bitiş listeleri

## Üretim / Operasyon

- Üretim planı / gerçekleşen raporları
- Fire ve kalite raporları
- Makine duruş raporları
- Kapasite kullanım raporları
- Vardiya raporları
- Stok ve hammadde takibi
- Sipariş karşılama performansı
- Bakım planları ve gerçekleşen bakım raporları

## Bilgi Teknolojileri

- Sistem erişim ve yetki raporları
- Yedekleme kontrol raporları
- Servis masası / ticket raporları
- Sistem kullanılabilirlik raporları
- Lisans envanteri ve yenileme takibi
- Güvenlik olayları ve log özetleri
- Yama / güncelleme durumu
- Donanım envanteri

## Hukuk / Uyum

- Sözleşme yenileme tarihleri
- Yasal bildirim ve yükümlülük takibi
- KVKK / bilgi güvenliği uyum kontrol listeleri
- Dava ve hukuki süreç durum raporları
- İmza / onay bekleyen doküman takibi

## Müşteri Hizmetleri

- Çağrı / talep hacmi raporları
- SLA ihlali takibi
- Müşteri memnuniyet raporları
- Şikâyet kategorilendirme
- Tekrarlayan problem analizi
- Açık taleplerin eskime (aging) raporları

## Lojistik / Tedarik Zinciri

- Sevkiyat takip raporları
- Teslimat gecikmeleri
- Depo stok raporları
- Stok devir hızı
- Nakliye maliyet raporları
- Tedarikçi teslimat performansı
- Minimum stok ve kritik malzeme uyarıları

## VeriShift İçin İlk MVP Seçim Kriterleri

İlk otomasyon senaryoları seçilirken aşağıdaki kriterler kullanılmalıdır:

1. İş en az haftalık tekrarlanıyor olmalı.
2. Süreç bugün ağırlıklı olarak manuel yürütülüyor olmalı.
3. Veri dijital kaynaklardan erişilebilir olmalı.
4. Başarı sayısal olarak ölçülebilmeli.
5. Yasal / finansal risk ilk MVP için yönetilebilir seviyede olmalı.
6. Süreç başka şirketlerde de benzer biçimde bulunmalı.
7. Otomasyon sonrası kazanılan zaman müşteriye kolayca gösterilebilmeli.

İlk MVP için, yüksek riskli resmi beyanları doğrudan göndermek yerine rapor hazırlama, veri kontrolü, mutabakat, konsolidasyon ve onay öncesi taslak üretimi gibi insan-onaylı süreçlerle başlamak daha güvenli olabilir.
