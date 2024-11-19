JavaScript, Brendan Eich tomonidan 1995-yilda yaratilgan bo‘lib, eng ko‘p ishlatiladigan veb-dasturlash tillaridan biridir. Dastlab dinamik veb-sahifalar yaratish uchun mo‘ljallangan. Skript — bu JS dasturi bo‘lib, u har qanday veb-sahifaning HTML kodiga qo‘shilishi mumkin. Sahifa yuklanganida, ushbu skriptlar avtomatik ravishda bajariladi.

JavaScript haqida qisqacha:
JavaScript dastlab dinamik veb-sahifalar yaratish uchun mo‘ljallangan bo‘lsa-da, bugungi kunda serverda yoki JavaScript dvigateli o‘rnatilgan deyarli har qanday qurilmada ishlatilishi mumkin. HTML va CSS dan keyin JavaScript uchinchi katta veb-texnologiyadir. U onlayn va mobil ilovalar, veb-serverlar, o‘yinlar va boshqa dasturlar yaratishda qo‘llanilishi mumkin.

JavaScript — obyektga yo‘naltirilgan dasturlash tili bo‘lib, veb-saytlar va ilovalarni yaratish uchun ishlatiladi. Ushbu til dastlab brauzerda ishlash uchun yaratilgan. Bugungi kunda JavaScript-ning server tomoni versiyasi, Node.js, onlayn va mobil ilovalar, real vaqt rejimida ishlaydigan dasturlar, onlayn striming ilovalari va video o‘yinlar yaratish uchun ishlatilishi mumkin.

JavaScript freymvorklari yoki kutubxonalari yordamida ishni soddalashtirish va dasturchilar vaqtini tejash mumkin. Bu kod kutubxonalari orqali dasturchilar monoton vazifalarga vaqt sarflashdan ko‘ra, ishlab chiqishning ijodiy jihatlariga e’tibor qaratishi mumkin.

Yangi boshlovchilar uchun JavaScript intervyu savollari va javoblari:
1. JavaScriptda mavjud bo‘lgan turli ma’lumot turlari qanday?
JavaScript o‘zgaruvchisining turini bilish uchun typeof operatoridan foydalanamiz.

1.1. Primiv turlar:
String - Belgilar ketma-ketligini ifodalaydi va qo‘shtirnoq bilan yoziladi.

javascript
Копировать код
var str = "Vivek Singh Bisht"; // qo‘shtirnoqli
var str2 = 'John Doe'; // bitta tirnoqli
Number - Butun yoki o‘nlik sonlarni ifodalaydi.

javascript
Копировать код
var x = 3; // butun son
var y = 3.6; // o‘nlik son
BigInt - Juda katta sonlarni saqlash uchun ishlatiladi.

javascript
Копировать код
var bigInteger = 234567890123456789012345678901234567890n;
Boolean - Mantiqiy qiymatni ifodalaydi: true yoki false.

javascript
Копировать код
var a = 2, b = 3, c = 2;
console.log(a == b); // false
console.log(a == c); // true
Undefined - O‘zgarmas ma’lumot kiritilmagan bo‘lsa, qiymati undefined.

javascript
Копировать код
var x;
console.log(x); // undefined
Null - Mavjud bo‘lmagan yoki noto‘g‘ri qiymatni bildiradi.

javascript
Копировать код
var z = null;
Symbol - ES6 versiyasida kiritilgan, noyob qiymatni saqlash uchun ishlatiladi.

javascript
Копировать код
var symbol1 = Symbol('symbol');
1.2. Noan’anaviy turlar (non-primitive):
Object - Ma’lumotlar yig‘indisini saqlash uchun ishlatiladi:

javascript
Копировать код
var obj1 = {
   x: 43,
   y: "Hello world!",
   z: function() {
      return this.x;
   }
};
Array - Ma’lumotlarni tartiblangan ro‘yxatda saqlaydi:

javascript
Копировать код
var array1 = [5, "Hello", true, 4.1];
2. JavaScriptda "Hoisting" tushunchasi nimani anglatadi?
"Hoisting" — bu JavaScriptning standart xatti-harakati bo‘lib, unda barcha o‘zgaruvchi va funksiya deklaratsiyalari avtomatik ravishda tepasiga ko‘chiriladi. Bu degani, o‘zgaruvchi va funksiyalar qaerda e’lon qilinganidan qat’i nazar, ular kodning yuqorisiga ko‘chiriladi.

Misollar:

javascript
Копировать код
hoistedVariable = 3;
console.log(hoistedVariable); // 3
var hoistedVariable;
Funksiyalar ham "hoist" qilinadi:

javascript
Копировать код
hoistedFunction();
function hoistedFunction() {
   console.log("Hello world!");
}
3. JavaScriptda "debugger" so‘zi nima uchun ishlatiladi?
"Debugger" kodni xatolarni tuzatish uchun ishlatiladi. Kodni bajarish vaqtida u bajarilishni to‘xtatib, xatoliklar haqida ma’lumot beradi.

4. "==" va "===" operatorlari o‘rtasidagi farq nimada?
== qiymatlarni taqqoslaydi (tipiga qarab emas).
=== qiymat va tipni ham taqqoslaydi.
Misol:

javascript
Копировать код
var x = 2, y = "2";
console.log(x == y);  // true
console.log(x === y); // false
5. "var" va "let" kalit so‘zlarining farqlari qanday?
var funksiya doirasiga ega, let esa blok doirasiga ega.
let 2015-yilda ES6 bilan joriy qilingan.
javascript
Копировать код
{
   var x = 10;
   let y = 20;
}
console.log(x); // 10
console.log(y); // Error, "y" block scope ichida
Qo‘shimcha savollar va ma’lumotlar bilan intervyu savollaringizni tayyorlang! 😊