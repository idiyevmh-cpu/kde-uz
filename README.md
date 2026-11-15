# KDE Plasma — Özbekça mahalliylaştiriş (l10n)

Uşbu repozitoriy **KDE Plasma** iş stoli muhiti va uning dasturlarini **özbek tiliga** (yangi lotin alifbosi asosida) tarjima qiliş loyihasidir. Loyiha açık manbali bölib, barça köngilli tarjimon va dasturçilar uçun oçiq!

---

## 📁 Repozitoriy tuzilişi

* **`Özbekça luğat/`** — tarjima qilinişi kerak bölgan tayyor `.po` va `.pot` şablon fayllari jildi.
* **`kde-uz.lokalize`** — **Lokalize** dasturi uçun tayyor loyiha sozlamalari fayli.
* **`terms.tbx`** — atamalar bir xilligini saqlaş uçun umumiy glossariy (lužat) bazasi.

---

## ⚠️ Muhim eslatma (Diqqat bilan öqing!)

**`Özbekça luğat`** jildida tayyor tarjima şablonlari mavjud, biroq ularni **100% töğri deb bölmaydi**.

* Şablonlardan matnni nusxalaşda (**Copy / Paste**) juda ehtiyot böling!
* Har bir satrni manba matn (inglizça) bilan soliştiib, ma'no jihatidan töğriligini, şuningdek, maxsus belgilar (`%1`, `%s`, `&`, HTML teglar) joyida ekanligini tekşiring.
* Avtomatik yoki xato tarjimalarni şundayliğiça qoldirmang.

---

## ✍️ Alifbo va imlo qoidalari

Loyihadagi barça tarjimalar **yangi özbek lotin alifbosi** qoidalariga qat'iy amal qilgan holda yozilişi şart:

| Eski yozuv | Yangi alifbo | Misol |
| :---: | :---: | :--- |
| **O‘ / O'** | **Ö / ö** | *Özbekça, öçiriş, bölma* |
| **G‘ / G'** | **Ğ / ğ** | *Töğri, luğat, yoğdu* |
| **Sh / sh** | **Ş / ş** | *Şablon, qöşiş, iş stoli* |
| **Ch / ch** | **Ç / ç** | *Oçıq, tarjimonlar uçun* |
| **’** (tutuq belgisi) | **ʼ** | *Ma'lumot, sun'iy* |

---

## 🤝 Loyihaga qanday hissa qöşiş mumkin?

Köngilli sifatida tarjima jarayoniga qöşiliş uçun quyidagi qadamlarni bajaring:

1. **Repozitoriyni nusxalang (Fork)** va öz kompyuteringizga yuklab oling:
   ```bash
   git clone [https://github.com/idiyevm-cpu/kde-uz.git](https://github.com/idiyevm-cpu/kde-uz.git)
