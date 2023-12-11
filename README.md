**Muhammad Ghifari Ramadhani
JCDSOL-011-022**

**HR ANALYTICS: EMPLOYEE PROMOTION DATA**

**Context**
  Sebuah perusahaan multinasional besar mempunyai 9 vertikal yang luas di seluruh organisasinya. Salah satu masalahnya adalah mengidentifikasi orang-orang yang tepat untuk promosi (hanya untuk posisi manajer ke bawah) dan mempersiapkan mereka tepat waktu. 
Promosi akhir hanya diumumkan setelah evaluasi dan hal ini menyebabkan penundaan transisi ke peran baru. Oleh karena itu, perusahaan memerlukan bantuan dalam mengidentifikasi kandidat yang memenuhi syarat pada checkpoint tertentu sehingga mereka dapat mempercepat seluruh siklus promosi.

Target :

0 : Tidak mendapatkan promosi

1 : Mendapatkan promosi

**Problem Statement :**

Mendapatkan sebuah promosi bagi seorang karyawan merupakan hal yang sangat membanggakan, namun prosesnya akan memakan waktu yang lama apabila perusahaan menargetkan semua karyawan tanpa melakukan penyaringan terlebih dahulu. Perusahaan ingin meningkatkan efisiensi waktu dan meningkatkan presisi pada target karyawan yang terbukti bahwa ia layak mendapatkan promosi jika dilihat dari kontribusinya selama bekerja dibawah perusahaan tersebut.

Jika mengadakan promosi tetapi tanpa dilihat tingkat presisi pada target karyawan yang layak mendapatkannya, resikonya fatal apabila seorang karyawan yang tidak selayaknya dipromosi namun mendapatkan promosi tersebut yang dapat berdampak besar kepada perusahaan tersebut.

**Goals :**

Maka berdasarkan permasalahan tersebut, perusahaan ingin memiliki kemampuan untuk memprediksi kemungkinan seorang karyawan yang layak untuk mendapatkan promosi pada perusahaan tersebut, sehingga dapat meminimalisir terjadinya dampak resiko tersebut.

Dan juga, perusahaan ingin mengetahui faktor apa yang dimiliki karyawan sebelumnya yang telah mendapatkan promosi agar dapat ditinjau juga untuk promosi karyawan yang berikutnya.

**Analytic Approach :**

Jadi yang akan kita lakukan adalah menganalisis data untuk menemukan pola yang membedakan karyawan yang layak mendapatkan promosi dan tidak layak mendapatkan promosi.

Kemudian kita akan membangun model klasifikasi yang akan membantu perusahaan untuk dapat memprediksi probabilitas seorang karyawan yang mendapatkan promosi dan tidak.

Dataset Source : https://www.kaggle.com/datasets/arashnic/hr-ana  
Note :  
- Dataset imbalanced

## <center>**Data Description**</center>

<center><table><center>
    <tr>
        <td><b>Variable</b></td>
        <td><b>Definition</b></td>
    </tr>
    <tr>
        <td>employee_id</td>
        <td>Unique ID for employee</td>
    </tr>
    <tr>
        <td>department</td>
        <td>Department of employee</td>
    </tr>
    <tr>
        <td>region</td>
        <td>Region of employment (unordered)</td>
    </tr>
    <tr>
        <td>education</td>
        <td>Education Level</td>
    </tr>
    <tr>
        <td>gender</td>
        <td>Gender of Employee</td>
    </tr>
    <tr>
        <td>recruitment_channel</td>
        <td>Channel of recruitment for employee</td>
    </tr>
    <tr>
        <td>no_of_trainings</td>
        <td>no of other trainings completed in previous year on soft skills, technical skills etc.</td>
    </tr>
    <tr>
        <td>age</td>
        <td>Age of Employee</td>
    </tr>
    <tr>
        <td>previous_year_rating</td>
        <td>Employee Rating for the previous year</td>
    </tr>
    <tr>
        <td>length_of_service</td>
        <td>Length of service in years</td>
    </tr>
    <tr>
        <td>awards_won?</td>
        <td>if awards won during previous year then 1 else 0</td>
    </tr>
    <tr>
        <td>avg_training_score</td>
        <td>Average score in current training evaluations</td>
    </tr>
    <tr>
        <td>is_promoted	(Target)</td>
        <td>Recommended for promotion</td>
    </tr>
</table>
