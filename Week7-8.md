# MINGGU 7 DAN 8
## React Js Hooks
**Hooks** adalah memudahkan penggunaan *Functinal Components* agar bisa menggunakan state dan lifecycle lainnya.

&nbsp;
Hooks yang sering digunakan adalah *useState dan useEffect*.

&nbsp;
### **UseState**
Penggunaan **useState** sedikit berbeda dengan **setState** / **state** di class components, namun pengertian dari **useState** itu sendiri sama dengan state biasa. **UseState** biasanya akan digunakan saat kamu menyimpan data suatu form yang nantinya akan di post ke api untuk di proses, selain itu kita bisa menyimpan data hasil get dari api kedalam state menggunakan **useState**.

### **UseEffect**
UseEffect merupakan hooks yang bisa digunakan untuk menggunakan lifecycle pada functional component dengan mudah. Penggunaan useEffect bisa dimasukan sebelum melakukan render useEffect sendiri biasanya ditempatkan dibawah useState.

### **Perbedaan Functional components dan Class components**
Kedua component menghasilkan hal yg sama, namun class menggunakan state, dan functional menggunakan state hooks.
### **PropTypes**
PropTypes adalah sebuah lib yang dapat membantu kamu untuk memeriksa data props yang dikirim agar sesuai dengan ekspektasi jika tidak selesai maka akan muncul pesan error.

## React Route Dom
React-router-dom adalah sebuah library yang dapat kita gunakan untuk membuat routing pada aplikasi React.js. Route adalah sebuah component yang mana akan menampilkan sebuah halaman apabila URL yang diberikan itu sesuai. React-router-dom bisa menerapkan server side rendering, yaitu tempat server mengembalikan halaman HTML yang siap dirender dan skrip JS yang diperlukan untuk membuat halaman menjadi interaktif.

## React Redux
React Redux adalah library untuk mengelola dan memperbarui status aplikasi. Terdapat beberapa konsep dasar redux yaitu **Store, Action, Dispatch**. Untuk mengambil data dari redux store kita dapat menggunakan salah satu react-redux API yaitu **useSelector**.

# MINGGU 8
## React Context
React Context adalah **library external JavaScript** yang dapat digunakan pada React.js, selain itu React Context termasuk state management pada React.js.
    
    import { createContext } from 'react';
    export const LevelHeadingContext = createContext;

**Alasan Menggunakan React Context**
1. Dapat menerapkan tema ke seluruh aplikasi dengan mendukung tema khusus.
2. Check Current Account

&nbsp;
Prop adalah Proses mengirimkan data melalui props yang dibutuhkan oleh component lain namun harus melalui beberapa component di bawahnya terlebih dahulu.

## Testing

**Alasan Menggunakan Testing**
1. Aplikasi bebas dari error dan bug.
2. Aplikasi berjalan sesuai dengan ekspektasi.
3. Meningkatkan kualitas dari sebuah software dan kepuasan pengguna.

### **Testing dibagi menjadi 2**
1. Manual Testing
2. Automated Testing

**Keunggulan Automated Testing**
1. Lebih reliable karena Manual Testing tetap berpotensi adanya kesalahan dan kekeliruan.
2. Lebih cepat dan efisien.
3. Mudah untuk dimaintain (Review, Edit, dan Add Collection of Tests).

**Regression merupakan?**

Tipe testing yang dilakukan untuk mengecek apakah suatu fitur baru yang ditambahkan ke dalam aplikasi akan membuat error atau bug pada fitur sebelumnya.

## React Testing Library (RTL)?
React Testing Library adalah Library yang memungkinkan seseorang untuk menguji komponen dengan meniru bagaimana pengguna sebenarnya akan berinteraksi dengan komponen tertentu.