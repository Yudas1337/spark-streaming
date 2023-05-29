# Praktikum Chapter 5

Nama : Yudas Malabi

Kelas : TI 3C / 20

NIM : 2041720054

1. Metode 1, Stateless Stream Processing

    menjalankan file network_wordcount.py dengan menjalankan 2 terminal, untuk eksekusi file dan sebagai netcat listener

    ![](img/metode_1_3.png)

    Selanjutnya, ubah interval yang awalnya 1 detik menjadi 5 detik

    ![](img/metode_1_2.png)

    ![](img/metode_1.png)

2. Metode 2, Statefull Stream Processing

    ![](img/metode_2.png)

    terdapat error pada script python, dimana mengakibatkan proses running shutdown secara otomatis.

3. Metode 3, Transformasi pada Park Streaming.

    ![](img/metode_3.png)

    terdapat error pada dataset, yaitu tuple index out of range.


# Tugas Teori Praktikum

1. Kode 1
    * sys.argv :
    * sys.stderr :
    * StreamingContext :
    * sc :
    * socketTextStream :
    * reduceByKey :
    * lambda line :
    * awaitTermination :
2. Kode 2
    * nc :
    * lk :
3. Kode 3
    * spark-submit :
    * master :
    * local[*] : 

4. Kode 4
    * ssc.checkpoint : 
    * parallelize :
    * updateStateByKey :
    * flatMap :
5. Kode 5
    * rdd.take(5) : 
    * transform : 
    * rdd.sortByKey(False) : 