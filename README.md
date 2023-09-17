# Migros

**Dataset Description**
1) Dosya
● train.csv - Training veri seti
● test.csv - Test veri seti
● transaction_header.csv – Fiş bilgileri
● transaction_sale.csv – Fişlerin içerisindeki ürünlerin bilgileri
● product_groups.csv – Kampanya kategorilerinin denk geldiği kategori kırılımları
● customeraccount.csv – cardnumber-individualnumber eşleşmesi
● customer.csv – Müşterilerin demografik bilgileri
● genel_kategoriler.csv – Genel kategori isimleri.

**Açıklamalar**

2) Promotion Train/Test
● individualnumber: Müşterinin kişi numarası
● category_number: Kampanyanın çıkıldığı kampanya kategorisi.
● hakkedis_amt: Kampanyadan yararlanabilmek için belirtilen kategoride yapılması gereken minimum harcama tutarı (TL)
● odul_amt: Kampanyadan yararlanıldığında elde edilecek ödül puan miktarı
● response: Müşterinin kampanyadan yararlanma durumu (1: Yararlandı, 0: Yararlanmadı) LABEL KOLONU

3) Transaction Header
● date_of_transaction: Fiş tarihi
● basketid: Fiş numarası
● cardnumber: Alışverişte kullanılan kart numarası (customeraccount tablosundaki cardnumber ile eşleşmektedir)
● is_sanal: Fişin karşılık geldiği alışverişin sanal olma durumu (1: Sanal Alışveriş, 0: Mağaza Alışverişi)

**Transaction Sale**
● basketid: Ürünün içerisinde geçtiği fişin numarası
● category_level_1: 1. Seviye Kategori (Kategori hiyerarşisinin en üst seviyesi)
● category_level_2: 2. Seviye Kategori
● category_level_3: 3. Seviye Kategori
● category_level_4: 4. Seviye Kategori (Kategori hiyerarşisinin en alt seviyesi)
● amount: Ürün tutarı
● quantity: Birim olarak satılan ürünlerde ürün sayısı, ağırlığı tartılarak satılan ürünlerde ürünün ağırlığı
● discount_type_1: Birinci tip indirimin yüzdesi
● discount_type_2: İkinci tip indirimin yüzdesi
● discount_type_3: Üçüncü tip indirimin yüzdesi

4) Product Groups
● category_number: Kampanyalarda kullanılan kategori.
● category_level_1: 1. Seviye Kategori (Kategori hiyerarşisinin en üst seviyesi)
● category_level_2: 2. Seviye Kategori
● category_level_3: 3. Seviye Kategori
● category_level_4: 4. Seviye Kategori (Kategori hiyerarşisinin en alt seviyesi)

5) Customer Account
● individualnumber: Promotion train/test tablosundaki individualnumber ile eşleşir.
● cardnumber: Transaction header tablosundaki customer_number ile eşleşir.

6) Customer
● individualnumber
● gender: Müşterinin cinsiyeti
● city code: Müşterinin il kodu
● dateofbirth: Müşterinin doğum yılı

**Size faydalı olabileceğini düşündüğünüz her türlü halka açık veriyi kullanabilirsiniz.**
