# Hisobot: parazitologiya mavzulari bo'yicha testlar

## 1. Fayllar va savollar soni
- `Testlar/001.xlsx` … `149.xlsx`: 149 ta fayl, jami 1493 ta savol (har faylda 10–11 ta).
- Format: `shablon.xlsx` (Question | A | B | C | D | E | Correct | Comment).
- Izohlar mavzu matnidan olingan «iqtibos» shaklida.

## 2. To'g'ri javob harflari taqsimoti
A = 299, B = 298, C = 299, D = 299, E = 298. Birorta faylda uch marta ketma-ket bir xil harf yo'q.

## 3. Uzun to'g'ri javoblar ulushi
To'g'ri javob eng uzun noto'g'ri javobdan 10% dan uzun: 260 ta savol (17,4%). Hech birida 30% chegarasi oshmagan.

## 4. Mavzu matnlari o'rtasidagi farqlar
1. 009: «O'zbekistonda parazitologiya maktabi» bo'limida avvalgi qoralamadan qolgan buzilgan jumla bor ("Avvalgi qoralamada tilga olingan boshqa mahalliy olimlarning nomlari (masalan, N.M. Matchanov va Sh.M." jumlasi uzilgan). Savollar bu jumlaga tayanmagan; matnni tuzatish kerak.
2. 002 va 003/004: gelmint turlari soni mavzular bo'yicha turlicha berilgan (250 dan ortiq tur va 287 tur). Savollarda har bir mavzu o'z matniga tayangan.

## 5. Matndagi [tasdiqlanmagan] belgili faktlar
`[tasdiqlanmagan ...]` shaklidagi belgi hech bir mavzuda topilmadi (079-mavzuda "tasdiqlanmagan" so'zi oddiy gap ichida uchraydi: homiladorlikda tasdiqlanmagan dori vositalari).

## Tekshiruv
- Qat'iy QA (build_tests.js): xato 0.
- Fayllar jszip bilan qayta o'qildi: savollar soni, izohda iqtibos, kirill aralashmasi yo'qligi, ketma-ket harflar tekshirildi: muammo 0.
- Tibbiy mazmunni mutaxassis tekshirishi kerak. Ba'zi noto'g'ri variantlar mavzu matnidagi iboralar bilan cheklanib tuzilgani uchun biroz sodda ko'rinishi mumkin.
