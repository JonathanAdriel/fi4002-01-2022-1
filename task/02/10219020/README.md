# 10219020
Jonathan Adriel


## materi sebelumnya
+ Tuliskan materi-materi sebelumnya yang telah diberikan dalam kuliah ini.
- Predator-prey
- Euler 
- Runge Kutta 
- Monte Carlo 
- Transformasi Fourier 
- Osilasi


## materi paling menarik
+ Tuliskan materi yang paling menarik yang telah diberikan dan jelaskan mengapa? 

Menurut saya, materi yang paling menarik adalah penentuan nilai pi dengan metode Monte - Carlo. Alasannya adalah ternyata sangat sederhana menentukan nilai pi dan cara ini sangat modern. 


## materi paling membosankan
+ Tuliskan materi yang telah diberikan yang paling membosankan dan jelaskan alasannya.

Menurut saya, tidak ada materi yang membosankan karena semua hal baru yang saya pelajari. 


## materi yang sudah dipami
+ Tuliskan materi-materi yang telah dipahami.

Secara keseluruhan, saya sudah memahami materi yang diberikan. 

## materi yang belum dipahami
+ Tuliskan materi-materi yang masih belum dipahami dan bagian mana yang belum serta ingin dipahami.

Secara keseluruhan, tidak ada materi yang tidak saya mengerti. Referensi di internet sudah tersedia sangat banyak. 

## contoh program
+ Buat suatu contoh program dalam Python dan sertakan di sini dengan hasil keluarnnya.

```python
# contoh program python

# Import the random module
import random
def unbiased_coin_toss():
    # Generate a random number from 0 to 1
    x = random.uniform(0, 1)
    # Probability that the number falls between 0 and 0.5 is 1/2
     
    if x > 0.5:
        # Heads for True
        return True
    else:
        # Tails for False
        return False
        
prob = []
 
# Make 1000 experiments
for i in range(1000):
     
    # Each experiment have 10 coin tosses
    N = 10
    results = []
 
    # Toss the coin 10 times and store that in a list
    for i in range(N):
        result = unbiased_coin_toss()
        results.append(result)
 
    n_heads = sum(results)
    p_heads = n_heads/N
    prob.append(p_heads)
 
# average the probability of heads over 1000 experiments
p_heads_MC = sum(prob)/1000
 
print("Probability is {:.3f}".format(p_heads_MC))

Hasilnya adalah

```
Probability is 0.499



## cara perkuliahan
+ Tuliskan pendapat Anda mengenai cara perkuliahan selama ini dan cantumkan usulan untuk perkuliahan setelah UTS.

Perkuliahan terhambat karena internet yang kurang bagus di kelas. Setelah UTS, saya usulkan kuliah dilakukan secara online. 

## topik sistem fisis
+ Tuliskan sistem fisis yang menarik bagi Anda untuk dikaji lebih dalam dan jelaskan alasannya mengapa.

Menurut saya, sistem fisis yang menarik untuk dikaji adalah sistem granular karena banyak variasi yang bisa dilakukan. Selain itu, sistem fluida juga menarik untuk dikaji. 

## simulasi dan visualisasi
+ Apakah Anda tertarik dengan simulasi dan visualisasi? Jelaskan topik yang ingin Anda simulasikan / visualisasikan serta cantumkan alasannya dan perkiraan pusataka Python yang perlu digunakan.

Saya tertarik untuk simulasi dan visualisasi. Topik yang ingin saya simulasi adalah pertumbuhan penduduk antar negara karena saya ingin melihat pola pertumbuhan penduduk yang berbeda antar negara. Referensi : 

https://eng.libretexts.org/Bookshelves/Environmental_Engineering_(Sustainability_and_Conservation)/Book%3A_Introduction_to_Environmental_Science_(Zehnder_et_al.)/2%3A_Population_Ecology/2.2%3A_Population_Growth_Models
