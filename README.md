# **FINAL PROJECT ANMINVESTING**

<img src="Logo.png">

# **INTRODUCTION**

Group Member:
1. Aan Nurliyanah
2. Ajeng Nilta Adriani
3. Fachmi Maris F.
4. Muhammad Fawwaz Dynoeputra Isnandar
5. Ropiudin

Dataset pada penilitian ini adalah data yang berisi data berdasarkan Kuesioner yang diisi Calon Nasabah untuk mengetahu klasifikasi risk profile calon nasabah sebelum melakukan investasi reksadana. Berdasarkan risk profile dari calon nasabah maka kami akan memberikan rekomendasi produk reksadana mana yang cocok untuk dipilih calon nasabah. Selain memberikan rekomendasi jenis dan produk reksadana, kelompok kami akan memberikan forecasting harga dari reksadana tersebut untuk 4 minggu ke depan.


|      `COLUMN`      | DESCRIPTION                                                                                                       |
| :----------------: | :---------------------------------------------------------------------------------------------------------------- |
|    `Age`    | Informasi tentang umur                                                                                                       |
|      `Expenses`      | Informasi tentang persentase biaya yang dikeluarkan dari income yang didapatkan                                                                        |
|  `Financial Status`   | Informasi tentang komisi perbandingan antara utang dengan asset                                                            |
|     `Experience`      | Informasi tentang pengalaman Nasabah dalam berinvestasi                                                               |
|    `Estimated Period`    | Informasi tentang jangka waktu Nasabah dalam melakukan investasi)                                                              |
|      `Scenario`      | Informasi tentang perbandingan antara mendapatkan keuntungan dan kerugian dalam berinvestasi                                                          |
|   `Unwilling toAccpet`   | Informasi tentang toleransi kerugian yang di harapkan oleh Nasabah)                                                         |
|  `Sum_Scores`   | Klasifikasi profile pada Nasabah                                        |

AGE :    
- Over 55 years (1)
- 45 - 55 years (2)
- 35 - 44 years (3)
- Under 35 Years (4)

EXPENSES :
- LEBIH DARI 75 % dari income (1)
- 50-75 % dari income (2)
- 25-50% dari income (3)
- Dibawah 25% (4)

FINANCIAL STATUS :
- debts > asset (1)
- debts = asset (2)
- debts < asset (3)
- have invest of pension (4)

EXPERIENCE :
- Bank Deposit (1)
- Bonds (Obligasi) (2)
- Fixed Income (Pendapatan Tetap) (3)
- High Rate Asset (4)

ESTIMATED PERIOD :
- Under 1 year (1)
- 1 - 3 year (2)
- 3 - 5 year (3)
- Over 5 year (4)

SCENARIO :
- return 2.5% loss 0% (1)
- return 7% loss 1% (2)
- return 15% loss 5% (3)
- return 25% loss 15% (4)

UNWILLING TO ACCEPT (**TOLERANSI KERUGIAN**):
- Below 5% (1)
- 5-10% (2)
- 10-20% (3)
- Above 20% (4)

SUM SCORES : 
1. "<10"   = Low Risk (**Very Cautious**)
2. "11-15" = Low to moderate Risk (**Cautious**)
3. "16-21" = Moderate to moderately high risk (**Balanced**)
4. "22-26" = High Risk (**Adventurous**)
5. ">26"   = Very High risk (**Speculative**)

# **OBJECTIVES**

The objectives in this final project 
1. Classification Customer Ris Profile 
2. Give Recommendation Based on Risk Profile Customer
3. Prediction price high and low forecasting 

# **CONCLUSION**

Dari Overall analysis dapat disimpulkan bahwa : 
1. Pada final project ini dilakukan pembuatan model machine learning Supervised Classification untuk mengetahui risk profile customer yang terdiri dari 10.000 entri data dan 8 kolom.
2. Dilakukan pembuatan pipeline pada proses preprocessing dan modeling
3. Risk Profile Customer ditentukan dari kuesioner nasabah yang akan melakukan investasi reksa dana.
4. Rekomendasi klasifikasi Reksa Dana berdasarkan Risk Profile yaitu : 
   ```
   a. Low Risk (Very Cautious)
   b. Low to moderate Risk (Cautious)
   c. Moderate to moderately high risk (Balanced)
   d. High Risk (Adventurous)
   e. Very High risk (Speculative)
   ```
5. Model Machine Learning yang digunakan yaitu Model SVM
6. Berdasarkan hasil diperoleh model terbaik yaitu model SVM dengan nilai accuracy 99%
