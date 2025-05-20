# Operator Penugasan (Assignment) ✍️

Operator penugasan digunakan untuk **menetapkan nilai ke dalam sebuah variabel**. Artinya, kita memberi tahu JavaScript bahwa "nilai ini sekarang milik variabel itu."

Selain `=`, ada juga bentuk-bentuk penugasan lain yang lebih ringkas dan sering digunakan dalam operasi matematika.

---

## Daftar Operator Penugasan 🤔

| Operator | Fungsi                     | Contoh                             |
| -------- | -------------------------- | ---------------------------------- |
| =        | Menetapkan nilai           | `x = 5`                            |
| +=       | Menambahkan dan menetapkan | `x += 3` (sama dengan `x = x + 3`) |
| -=       | Mengurangi dan menetapkan  | `x -= 2` (sama dengan `x = x - 2`) |
| \*=      | Mengalikan dan menetapkan  | `x *= 4`                           |
| /=       | Membagi dan menetapkan     | `x /= 5`                           |
| %=       | Modulus dan menetapkan     | `x %= 3`                           |

---

## Contoh Kode 📦

```js
let x = 10;

x += 5; // x = x + 5
console.log(x); // Output: 15

x *= 2; // x = x * 2
console.log(x); // Output: 30
```

---

✅ Dengan operator penugasan, kita bisa menulis kode yang lebih **ringkas** dan **efisien**. Cocok banget dipakai saat kita ingin melakukan operasi berulang pada variabel yang sama tanpa harus menuliskannya berkali-kali.

---

## Penjelasan Langkah demi Langkah 🧠

```js
let x = 10;
```

👉 Pertama, kita buat variabel `x` dan beri nilai awal 10.

```js
x += 5;
```

👉 Ini sama dengan `x = x + 5`, jadi:

- `x = 10 + 5`
- Hasilnya `x = 15`

```js
x *= 2;
```

👉 Ini sama dengan `x = x * 2`, jadi:

- `x = 15 * 2`
- Hasilnya `x = 30`

🎉 Jadi hasil akhirnya:

1. Nilai awal: `x = 10`
2. Setelah `x += 5`: `x = 15`
3. Setelah `x *= 2`: `x = 30`

Dengan begitu, kamu bisa lihat bagaimana operator penugasan mempersingkat penulisan operasi yang umum dilakukan. 💡
