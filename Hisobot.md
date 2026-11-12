# Hisobot: parazitologiya mavzulari bo'yicha testlar

## 1. Fayllar va savollar soni
- `Testlar/001.xlsx` … `149.xlsx`: 149 ta fayl, jami 1493 ta savol (har faylda 10–11 ta).
- Format: `shablon.xlsx` (Question | A | B | C | D | E | Correct | Comment).
- Izohlar mavzu matnidan olingan «iqtibos» shaklida.

## 2. To'g'ri javob harflari taqsimoti
A = 299, B = 298, C = 299, D = 299, E = 298. Birorta faylda uch marta ketma-ket bir xil harf yo'q.

## 3. Uzun to'g'ri javoblar ulushi
To'g'ri javob eng uzun noto'g'ri javobdan 10% dan uzun: 254 ta savol (17,0%). Hech birida 30% chegarasi oshmagan.

## 4. Mavzu matnlari o'rtasidagi farqlar
1. 009: «O'zbekistonda parazitologiya maktabi» bo'limida avvalgi qoralamadan qolgan buzilgan jumla bor ("Avvalgi qoralamada tilga olingan boshqa mahalliy olimlarning nomlari (masalan, N.M. Matchanov va Sh.M." jumlasi uzilgan). Savollar bu jumlaga tayanmagan; matnni tuzatish kerak.
2. 004: odamda parazitlik qiluvchi gelmint turlari soni bir mavzuning ichida turli manbalarga ko'ra 250 dan ortiq va 287 deb berilgan. Savolda faqat "250 dan ortiq" varianti ishlatilgan. Mavzular o'rtasidagi boshqa ziddiyatlar to'liq qo'lda solishtirilmagan.

## 5. Matndagi [tasdiqlanmagan] belgili faktlar
`[tasdiqlanmagan ...]` shaklidagi belgi hech bir mavzuda topilmadi (079-mavzuda "tasdiqlanmagan" so'zi oddiy gap ichida uchraydi: homiladorlikda tasdiqlanmagan dori vositalari).

## Tekshiruv
- Qat'iy QA (build_tests.js): xato 0.
- Fayllar jszip bilan qayta o'qildi: savollar soni, izohda iqtibos, kirill aralashmasi yo'qligi, ketma-ket harflar tekshirildi: muammo 0.
- Tibbiy mazmunni mutaxassis tekshirishi kerak. Ba'zi noto'g'ri variantlar mavzu matnidagi iboralar bilan cheklanib tuzilgani uchun biroz sodda ko'rinishi mumkin.

## Sifat tekshiruvi (ikkinchi o'tish)
Savollarning mazmuni alohida sifat tekshiruvidan o'tkazildi (013–149): kesilgan yoki javobni tasdiqlamagan iqtiboslar almashtirildi, to'g'ri javobning parafrazasi bo'lgan yoki bir so'z farqli "tuzoq" variantlar, ma'nosiz variantlar va hujjat ilovasiga havola qilgan savollar yangilandi. Taxminan yarmi savollar o'zgargan. Qat'iy QA qayta o'tkazildi: xato 0.
