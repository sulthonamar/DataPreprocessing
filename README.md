# DataPreprocessing

Stage 1 - Data Preprocessing untuk Bootcamp Data Science 45. Dilakukan dengan menggunakan Dataset "Holiday Package Prediction" yaitu Travel.csv. 
"Travel.Com" company wants to enable and establish a viable business model to expand the customer base. One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information. The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being.However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

Dataset Feature Descriptions:
CustomerID : Unique customer ID
ProdTaken : Whether or not the customer bought a product
Age : Customer age
TypeofContact : How was the customer contacted
CityTier : City tier depends on the development of a city, population, facilities, and living standards
DurationOfPitch : Duration of the pitch by a salesperson to the customer
Occupation : Occupation of customer
Gender : Gender of customer
NumberOfPersonVisiting : Total number of persons planning to take the trip with the customer
NumberOfFollowups : Total number of follow-ups has been done by the salesperson after the sales pitch
ProductPitched : Product pitched by the salesperson
PreferredPropertyStar : Preferred hotel property rating by customer
MaritalStatus : Marital status of customer
NumberOfTrips : Average number of trips in a year by customer
Passport : If customer has passport or not
PitchSatisfactionScore : Sales pitch satisfaction score
OwnCar : Does the customer own a car
NumberOfChildrenVisiting : Number of children traveling with the customer
Designation : Designation of the customer in the current organization
MonthlyIncome : Gross monthly income of the customer

Tugas Stage 1 - Data Preprocessing :
1. Data Cleansing (50 poin) 
Lakukan pembersihan data, sesuai yang diajarkan di kelas, seperti:
A. Handle missing values
B. Handle duplicated data
C. Handle outliers
D. Feature transformation
E. Feature encoding
F. Handle class imbalance
Di laporan homework, tuliskan apa saja yang telah dilakukan dan metode yang digunakan.
* Tetap tuliskan jika memang ada tidak yang perlu di-handle (contoh: “Tidak perlu feature 
encoding karena semua feature sudah numerical” atau “Outlier tidak di-handle karena 
akan fokus menggunakan model yang robust terhadap outlier”)

2. Feature Engineering (35 poin) 
Cek feature yang ada sekarang, lalu lakukan:
A. Feature selection (membuang feature yang kurang relevan atau redundan)
B. Feature extraction (membuat feature baru dari feature yang sudah ada)
C. Tuliskan minimal 4 feature tambahan (selain yang sudah tersedia di dataset) yang 
mungkin akan sangat membantu membuat performansi model semakin bagus (ini hanya 
ide saja, untuk menguji kreativitas teman-teman, tidak perlu benar-benar dicari datanya 
dan tidak perlu diimplementasikan)
* Untuk 2A & 2B, tetap tuliskan jika memang tidak bisa dilakukan (contoh: “Semua feature 
digunakan untuk modelling (tidak ada yang dihapus), karena semua feature relevan”)

3. Git (15 poin) 
Upload project teman-teman di sebuah repository git. Berkolaborasilah di Git jika ada 
perubahan version dari waktu ke waktu. 
A. Buat Repository Git
B. Upload file notebook atau file pengerjaan lainnya pada repository tersebut
Untuk file README, dapat merupakan summary dari proses data preproses yang telah 
dilakukan. Boleh menggunakan repositori yang sama atau membuat baru. 

