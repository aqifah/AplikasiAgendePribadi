# AplikasiAgendePribadi
Nor Aqifah-2310010196-UTS


# Aplikasi Agenda Pribadi (Java Swing)

## Deskripsi Program

Aplikasi Agenda Pribadi adalah aplikasi berbasis Java Swing yang
digunakan untuk mencatat kegiatan pribadi. Program ini memungkinkan
pengguna menambahkan kegiatan, jam, dan tanggal menggunakan kalender,
menampilkan data ke tabel, menghapus data, membersihkan input, serta
menyimpan data ke file `.txt`.

## Fitur Aplikasi

-   Menambahkan kegiatan
-   Memilih tanggal menggunakan JDateChooser
-   Menampilkan data dalam tabel
-   Menghapus baris tabel
-   Membersihkan form input
-   Menyimpan seluruh agenda ke file teks

## Konsep OOP yang Digunakan

### 1. Class

`AplikasiAgendaPribadi` merupakan class utama yang menjadi window
aplikasi:

    public class AplikasiAgendaPribadi extends javax.swing.JFrame

### 2. Constructor

    public AplikasiAgendaPribadi() {
        initComponents();
    }

Berfungsi menginisialisasi komponen GUI.

### 3. Atribut

Atribut GUI dan variabel program: - textKegiatan, textPukul
(JTextField) - DateCalendar (JDateChooser) - Tbdata (JTable) - Button:
buttonTambahkan, buttonHapus, buttonBersihkan, buttonSimpan,
buttonKeluar - Label dan Panel pendukung

### 4. Object

Objek dari berbagai class Swing: - JTextField - JDateChooser - JTable -
JButton - JPanel - JLabel - Serta objek utama:
`new AplikasiAgendaPribadi()`

### 5. Method

Method utama: - buttonTambahkanActionPerformed() -
buttonHapusActionPerformed() - buttonBersihkanActionPerformed() -
prosesSimpan() - buttonKeluarActionPerformed()

### 6. Abstraction

Menggunakan komponen Swing tanpa memahami detail implementasi internal.

### 7. Encapsulation

Atribut dibuat private agar hanya dapat diakses dalam class.

### 8. Inheritance

Class menggunakan pewarisan:

    extends javax.swing.JFrame

### 9. Polymorphism

Event listener meng-override method bawaan dan menjalankan perilaku
berbeda pada tiap tombol.

## Diagram UML (Teks)

    +---------------------------------------------------------+
    |                 AplikasiAgendaPribadi                   |
    |---------------------------------------------------------|
    | - textKegiatan : JTextField                             |
    | - textPukul : JTextField                                |
    | - DateCalendar : JDateChooser                           |
    | - Tbdata : JTable                                       |
    | - buttonTambahkan : JButton                             |
    | - buttonHapus : JButton                                  |
    | - buttonBersihkan : JButton                              |
    | - buttonSimpan : JButton                                 |
    | - buttonKeluar : JButton                                 |
    | - jLabel1,jLabel2,jLabel3,jLabel4 : JLabel              |
    | - jPanel1 : JPanel                                      |
    |---------------------------------------------------------|
    | + AplikasiAgendaPribadi()                               |
    | - initComponents()                                      |
    | + main()                                                |
    | - buttonTambahkanActionPerformed()                      |
    | - buttonHapusActionPerformed()                           |
    | - buttonBersihkanActionPerformed()                      |
    | - buttonKeluarActionPerformed()                         |
    | - prosesSimpan()                                        |
    +---------------------------------------------------------+
              ^
              |
           JFrame

## Cara Menjalankan

1.  Import project ke NetBeans / IntelliJ
2.  Pastikan library JDateChooser tersedia
3.  Jalankan file AplikasiAgendaPribadi.java
4.  Aplikasi siap digunakan
----------------------------------------------------
Nama: Nor Aqifah
NPM: 2310010196
