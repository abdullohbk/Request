## 1 Meta teglari vazifalari

meta tegi HTML hujjat haqidagi metama'lumotlarni belgilaydi. Metadata - bu ma'lumotlar haqidagi ma'lumotlar (ma'lumotlar).

meta teglari har doim head elementi ichiga kiradi va odatda belgilar to'plamini, sahifa tavsifini, kalit so'zlarni, hujjat muallifini va ko'rish oynasi sozlamalarini belgilash uchun ishlatiladi.

Metadata sahifada ko'rsatilmaydi, lekin mashinada tahlil qilinadi.

Metadata brauzerlar (tarkibni qanday ko'rsatish yoki sahifani qayta yuklash), qidiruv tizimlari (kalit so'zlar) va boshqa veb-xizmatlar tomonidan qo'llaniladi.

Veb-dizaynerlarga meta yorlig'i orqali ko'rish oynasini (veb-sahifaning foydalanuvchining ko'rinadigan maydoni) nazorat qilish imkonini beradigan usul mavjud (quyidagi "Ko'rish portini o'rnatish" misoliga qarang).

## 2 Pseudo class va Pseudo element

Pseudo-klass - ma'lum bir holatda bo'lgan elementlarni tanlaydigan selektor, masalan. ular o'z turining birinchi elementidir yoki ular sichqoncha ko'rsatkichi bilan olib kelinmoqda. Ular, odatda, siz hujjatingizning qaysidir qismiga sinf qo'llagan bo'lsangiz, ko'pincha belgilashingizdagi ortiqcha sinflarni qisqartirishga yordam beradi va sizga yanada moslashuvchan, qo'llab-quvvatlanadigan kodni beradi.

Pseudo-elementlar xuddi shunday yo'l tutadi. Biroq, ular mavjud elementlarga sinfni qo'llash o'rniga, belgilashga butunlay yangi HTML elementini qo'shgandek harakat qilishadi.

Psevdo-elementlar qo'sh nuqta bilan boshlanadi ::. ::befor psevdoelementga misol.

## 3 Mixin va Extend

@mixin bir necha marta qayta ishlatilishi kerak bo'lgan CSS kodini guruhlash uchun ishlatiladi. @extend SASS da boshqa CSS selektoridan xususiyatlarni meros qilib olish (ulashish) uchun ishlatiladi. @extend elementlar deyarli bir xil yoki bir xil bo'lsa foydali bo'ladi. Ularning orasidagi asosiy farq ularning kompilyatsiya qilingan CSS faylida.

## 4 Javascript data types


Javascriptda 8ta data type mavjud :

- 1. String
- 2. Number
- 3. Bigint
- 4. Boolean
- 5. Undefined
- 6. Null
- 7. Symbol
- 8. Object

va bular ikki turga bo'linadi: 1 Primative 2 Non Primative (reference)

#### Primative tur bu: faqat bitta turdagi ma'lumotni o'zida saqlaydigan ma'lumot turi bu turga quyidagilar kiradi

- 1. String
- 2. Number
- 3. Bigint
- 4. Boolean
- 5. Undefined
- 6. Null
- 7. Symbol

#### Non Primative (reference) tur bir nechta qiymatni o'zida saqlovchi data type va bu tur o'z ichiga faqat bir dona data type ni olgan

-  Object

## 5 Variables difference 

let va var kalit so'zlari JavaScript-da yangi o'zgaruvchilarni e'lon qiladi. Let va var o'rtasidagi farq ular yaratadigan o'zgaruvchilar doirasidadir:

Let tomonidan e'lon qilingan o'zgaruvchilar faqat ular aniqlangan blokda mavjud.
var tomonidan e'lon qilingan o'zgaruvchilar ular e'lon qilingan funktsiyada mavjud.