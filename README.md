# Hadoop & Hive Practicum

## 📌 Deskripsi
Project ini merupakan implementasi Hadoop dan Hive menggunakan LXC container sebagai bagian dari praktikum Big Data.

## 📊 Architecture
Hadoop (HDFS + YARN) digunakan sebagai distributed storage,
sedangkan Hive digunakan sebagai data warehouse untuk query SQL.

## 🎯 Tujuan
- Memahami konsep Big Data
- Implementasi Hadoop ecosystem
- Query data menggunakan Hive
  
## ⚙️ Tools & Teknolog
* Hadoop 3.3.6
* Hive 3.1.2
* Ubuntu (LXC Container)

## 🚀 Langkah-langkah
1. Install Hadoop
2. Konfigurasi HDFS (core-site.xml, hdfs-site.xml)
3. Menjalankan Hadoop (start-all.sh)
4. Install Hive
5. Konfigurasi Hive
6. Menjalankan query SQL di Hive

## ✅ Hasil
* Hadoop berhasil dijalankan (NameNode, DataNode, ResourceManager, NodeManager)
* Hive berhasil dijalankan
* Query SQL berhasil dieksekusi

## 🧪 Contoh Query
```sql
SHOW DATABASES;
CREATE DATABASE latihan;
USE latihan;

CREATE TABLE mahasiswa (
  nama STRING,
  umur INT
)
ROW FORMAT DELIMITED
FIELDS TERMINATED BY ',';

SELECT * FROM mahasiswa;
```

## 📸 Screenshot
