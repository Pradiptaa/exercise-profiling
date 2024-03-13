# Exercise Profiling

---

<details>
<summary>

## JMeter Screenshots
</summary>

- /all-student before optimization
  ![](https://cdn.discordapp.com/attachments/784424703447400489/1217449823779950632/allstud_before.png?ex=66041181&is=65f19c81&hm=6436eabb4071e5d3e5010d0a1ef688d53ed4a9f33db683a3e561fb7f4fe3728c&)
- /all-student-name before optimization
  ![](https://cdn.discordapp.com/attachments/784424703447400489/1217449824048381982/allstudname_before.png?ex=66041181&is=65f19c81&hm=cb9504398bc160e441275501cc4dfd035c38220b858c628c221d36a98aecce36&)
- /highest-gpa before optimization
  ![](https://cdn.discordapp.com/attachments/784424703447400489/1217449824304103534/highestgpa_before.png?ex=66041181&is=65f19c81&hm=3d5eb179491ae935b0ab52af138ff507eb2d525497ec8d683e91d0fd290ee2a3&)
- /all-student optimized
  ![](https://cdn.discordapp.com/attachments/784424703447400489/1217451932310962277/allstud_after.png?ex=66041377&is=65f19e77&hm=bbb83084ca31cddff9c1296d789c84e53e4ba6992567226d448dbbb1f1d4cd7a&)
- /all-student-name optimized
  ![](https://cdn.discordapp.com/attachments/784424703447400489/1217451932621213756/allstudname_after.png?ex=66041377&is=65f19e77&hm=8c67dec3305f825f749584742be955224e704fbeefb32edffdcef50735f59a94&)
- /highest-gpa optimized
  ![](https://cdn.discordapp.com/attachments/784424703447400489/1217451932915073034/highestgpa_after.png?ex=66041377&is=65f19e77&hm=b311d92b10d79c07be1044db20a21250e58bf85e761ce086519d1bc999ecb75a&)

</details>

<details>
<summary>

## Modul 5
</summary>

1. <strong>What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?</strong> <br>
   - JMeter: Untuk menguji seberapa baik aplikasi berjalan di bawah tekanan banyak pengguna.
   - IntelliJ Profiler: Untuk menemukan dan memperbaiki bagian kode yang membuat aplikasi lambat atau menggunakan banyak memori. <br><br>
2. <strong>How does the profiling process help you in identifying and understanding the weak points in your application?</strong> <br>
   Proses profiling membantu mengidentifikasi titik lemah aplikasi dengan cara menunjukkan bagian kode yang memperlambat aplikasi, mengungkap penggunaan memori yang tidak efisien, dan mendeteksi masalah concurrency seperti deadlocks. Ini memungkinkan pengembang untuk membuat perubahan yang diperlukan untuk meningkatkan kinerja, membuat aplikasi lebih cepat, lebih efisien, dan lebih stabil.<br><br>
3. <strong>Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?</strong> <br>
   Ya, IntelliJ Profiler efektif dalam membantu analisis dan identifikasi bottleneck dalam kode aplikasi Anda. Alat ini menyediakan wawasan mendalam tentang bagaimana aplikasi berjalan, termasuk penggunaan CPU, penggunaan memori, dan waktu eksekusi metode. Dengan informasi ini, pengembang dapat menemukan bagian kode yang tidak efisien atau yang memerlukan optimasi lebih lanjut, sehingga membantu meningkatkan kinerja keseluruhan aplikasi. Fitur visual dan analitis yang disediakan IntelliJ Profiler membuat proses penemuan dan pemecahan masalah menjadi lebih intuitif dan efisien. <br><br>
4. <strong>What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?</strong> <br>
    Tantangan utama yang dihadapi adalah pemahaman terhadap testing dan profiling yang dilakukan. Dengan membaca dan menyimak tantangan ini dapat teratasi. <br><br>
5. <strong>What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?</strong> <br>
   Keuntungan utama dari penggunaan IntelliJ Profiler adalah analisis Performa Real-time yang memungkinkan untuk melihat bagaimana kode berjalan dalam kondisi nyata, membantu mengidentifikasi masalah yang mungkin tidak muncul selama pengujian standar. <br><br>
6. <strong>How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?</strong> <br>
    Menghapadi tidak konsisten-nya testing dengan mengulangi kedua tes untuk memastikan hasil yang akurat dan juga menganalisis konteks pengujian JMeter dan IntelliJ Profiler untuk memahami perbedaan kondisi atau setup. <br><br>
7. <strong>What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?</strong> <br>
   Saya mempercepat program dengan menerapkan metode parallelStream(). Melalui IntelliJ Profiler, saya berhasil mengidentifikasi dan memperbaiki bagian yang paling memperlambat program. Karena aplikasi ini kekurangan unit test, saya melakukan pemeriksaan hasil pre dan post-optimisasi untuk menjamin tidak ada fungsi yang terganggu.

</details>
