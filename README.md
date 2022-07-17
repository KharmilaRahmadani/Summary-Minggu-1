# **SUMMARY MINGGU 1** #![coding css]


# ***DAY 1*** #
## **Command Line Interface (CLI)** ##

**CLI** = **User** dapat menjalankan **perintah** berupa **teks** dan memberikan intruksi pada suatu komputer agar dapat mengerjakan tugas tertentu. 

>Note :  program yang menerima perintah, kemudian meneruskan perintah tersebut ke system untuk dieksekusi disebut **Shell**.

**Contoh CLI :**
1. sh
2. bash
3. zsh
4. cmd.exe


`Ada beberapa perintah atau command yang dapat diinput ke dalam direktori :`

>**1. Navigation**

a. **pwd (Print working Directory) :** Mencari path dari direktori yang digunakan saat ini.

b. **ls (lists) :** Menampilkan daftar file dan folder

c. **cd (change directory) :** Perintah untuk pindah folder

>**2. File Manipulation**

a. **head**

b. **tail**

b. **cat**

`Perintah yang digunakan untuk membuat files & direktori :`

a. **touch :** membuat file

b. **mkdir :** membuat direktori

`Perintah yang digunakan untuk menyalin, memindahkan, dan menghapus files & direktory :`

a. **cp :** menyalin file ke folder

b. **mv :** memindahkan file baru

c. **rm :** membuat file


# ***DAY 2*** #
## **Git & GitHub** ##
**Git** = digunakan untuk programmer dalam memversikan program kita.

>`Analogi :` membuat tugas di Ms.Word dengan nama "Hello World" sebagai versi 1, kemudian file tersebut di copy dan di paste dengan nama "Hello World to Everyone" sebagai versi 2

**Git** bertugas sebagai **Version Control System** yang **mencatat** setiap **perubahan** file (termasuk kose yang dibuat) pada suatu proyek baik dikerjakan secara **individu/tim**.

>Cara untuk membuka Git :
>1. Menggunakan **cmd**
>2. Menggunakan **powershell**
>3. Menggunakan **powerbash**

**Repository Git**

**Repository Git** = direktori proyek yang kita buat.

>Basic coding yang biasa digunakan untuk membuat direktori pada Repository Git:
>1. git add
>2. git commit
>3. git push

- **Fitur** yang **WAJIB** digunakan jika berkolaborasi dengan developer atau dalam tim adalah **Git Branch**.
- **Fitur** yang digunakan untuk **menyatukan** pekerjaan ke master file/branch utama yaitu branch MASTER disebut **Git Merge**.


# ***DAY 3*** #

## **Hypertext Markup Language (HTML)** ##
**HTML** = digunakan untuk **menampilkan konten** pada **browser**.
>*Note : 
>**HTML** BUKAN **bahasa pemrograman**. tetapi, bahasa untuk **Markup tulisan**.

>*Note : 
>**HTML** bersifat **statis**. Hanya bertugas dalam menampilkan konten yang diminta developer.

>**HTML** tidak bersifat **dinamis** mengolah data.

Sebagai **Programmer**, ada 2 tools yang digunakan untuk membuat HTML :
1. Browser
2. Code Editor

Salah satu code editor yang **banyak digunakan** oleh komunitas sesama developer adalah **Visual Code Editor (VSC)**. Hal tersebut dikarenakan adanya beberapa kelebihan :
- **Dapat digunakan pada Windows, Mac, dan Linux.**
- **Intellisense**
- **Run and Debug**
- **Built-in Git**
- **Extensions**

>Dalam **HTML Anatomy** HTML element didefinisikan sebagai :
**Opening tag, content, dan closing tag.**

Beberapa tag yang biasa digunakan adalah :
1. Heading
2. Paragraph
3. Hyperlink

>Beberapa Atribute/Properties HTML yang sering digunakan :
id, class, name, dll.

Tag terbagi menjadi 2 yaitu :
1. Single Tag/Singular Tag
2. Paired Tag

### **Attribute** ###
>**Attribute** = **properties** dari sebuah HTML Element.


### **HTML Form** ###
>**HTML Form** = membungkus seluruh input *interface* yang ada.

### **Semantic HTML** ###
>**Semantic HTML** = menggunakan elemen HTML yang sesuai dengan konten kebutuhan.

> **Kelebihan Semantic HTML :**
* Meningkatkan Accessibility (khususnya untuk para disabilitas).
* Meningkatkan SEO (*Search Engine Optimizer*). 
* Mudah dikelola.

### **Deploy HTML** ###
>**Deploy HTML** = proses sharing aplikasi yang telah dibuat agar bisa digunakan oleh orang lain.

>Cara mendeploy HTML
Solusi = [link to netlify](netlify.com)



# ***DAY 4*** #
## **Cascanding Style Sheet (CSS)** ##
**CSS** = bahasa yang digunakan untuk **mendesain** halaman web.

>**Fungsi :**

- **Mengubah warna**
- **Menggunakan font custom**
- **Editing text format**
- **Mengatur tata letak, dll.**

Ada 3 cara menggunakan CSS :
1. Inline Style = menggunakan CSS **langsung** pada attribut elemen HTML.
2. Internal HTML = menambahkan attribut CSS **di dalam terminal HTML**.
3. External CSS = menambhkan attribut CSS **di luar terminal HTML**.

### **Cara menghubungkan CSS Files dengan HTML** ###
> Note : Tidak ada aturan baku untuk penempatan path file .css.
>Namun harus dalam 1 folder project yang sama.

Contoh :
![coding css](https://user-images.githubusercontent.com/109120017/179403899-7b1c2a5b-1200-4cfa-a2c7-a318d2725d43.jpg)

### **Cara Mendesain elemen HTML pada CSS** ###
> Note : Ada beberapa cara yang dapat digunakan sesuai kebutuhan :

- CSS-Tag Name
- CSS-Class Name
- CSS-Multiple Class
- CSS-ID Name

### **Perbedaan ID Name dan Class Name** ###
**1. ID Name**
>**Gunakan** ID Name jika **hanya** ada 1 elemen pada file/halaman HTML.

>Contohnya :

>* navigation
>* footer

**2. Class Name**
>**Gunakan** Class Name jika akan ada **beberapa element HTML** yang memiliki styling/desain yang sama.

>Contohnya :

>* Kita ingin Heading Blog kita memiliki desain yang sama. 

>* Kita ingin setiap link memiliki styling/desain yang sama.

### **Chaining Selector** ###
Digunakan pada kondisi apabila :
>Memiliki 3 tag elemen HTML pada CSS namun kita ingin ada 1 elemen HTML yang memiliki styling berbeda.

![chaining selector](https://user-images.githubusercontent.com/109120017/179404016-0aaf1ddd-7483-4bf9-85dd-6a2daa6639bc.png)


### **Nested Element** ###
>Konsep CSS sama dengan HTML yaitu setiap element memiliki parent dan child.

### **!important CSS** ###

>!important CSS berada pada hirearki tertinggi dari **ID** dan **Class**.

>**Maksudnya** apabila kita menggunakan jenis styling ini, maka styling sebelumnya (ID Name atau Class Name) akan di override.


### **Multiple Selector** ###
>Styling jenis ini memungkinkan kita untuk membuat **code lebih efisien** dan **tidak melakukan hal yang sama berulang-ulang**.

### **Flexbox** ###
>**Flexbox** = satu cara yang digunakan untuk **mengatur layout**.

>Pengunaannya **mudah** dan **didukung** oleh **banyak browser**.





## **ALGORITMA & PSEUDOCODE** ##
### **Algoritma** ###
>**Algoritma** = penjelasan berupa cara-cara yang digunakan untuk menyelesaikan suatu masalah.

### **Kualitas Wajib dari Algoritma :** ###
* Input & Output harus didefinisikan terlebih dahulu dengan tepat.

> `Analogi : Membuat tumis kangkung`

> `Input : Kangkung Mentah`

> `Output : Tumis Kangkung`

* Setiap tahapan harus benar-benar jelas & tidak ambigu
* Algoritma seharusnya tidak mengandung suatu code pada bahasa pemrograman tertentu

### **Alasan Menggunakan Algoritma :** ###
* Programming itu = algoritma & struktur data
* Data struktur digunakan untuk mengelola data
* Algoritma akan menyelesaikan masalah menggunakan data tersebut

### **Contoh Algoritma Sederhana:** ###
![algoritma](https://user-images.githubusercontent.com/109120017/179404053-63976dd2-74ab-4f0d-a689-776bbc36aa9a.png)


### **Pseudocode** ###
> **Pseudocode** = tools/alat untuk menuliskan algoritma yang umumnya bahasa inggris sebelum diterapkan ke bahasa pemrograman tertentu.

**Cara Menulis Pseudocode**
>1. Menggunakan HURUF BESAR pada kata kunci (key commands). 
**CONTOH :** IF number is > 10 THEN …

> 1. Statement =  1 baris 
>2. Gunakan indentasi
> 3. Harus spesifik
> 4. Harus simpel

**Contoh :**








