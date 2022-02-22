# Hacktiv8 Phase 1: Graded Challenge 2

Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada konsep Classification terutama Logistic Regression dan SVM.

---

By [Rifky Aliffa](https://github.com/Penzragon)

![weather](https://images.ctfassets.net/hrltx12pl8hq/6TIZLa1AKeBel0yVO7ReIn/1fc0e2fd9fcc6d66b3cc733aa2547e11/weather-images.jpg?fit=fill&w=800&h=300)

## Dataset

Dataset yang digunakan pada project ini adalah dataset yang berisi tentang cuaca harian dari berbagai stasiun cuaca di Australia selama 10 tahun. Dataset ini berisi 145460 baris dengan 23 kolom yang diantaranya adalah date, location, MinTemp, MaxTemp, dan masih banyak lagi. Dataset dapat dilihat di [Kaggle](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package).

Keterangan dari kolom dataset ini adalah:

| Feature       | Description                                                                                                            |
| ------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Date          | The date of observation                                                                                                |
| Location      | The common name of the location of the weather station                                                                 |
| MinTemp       | The minimum temperature in degrees celsius                                                                             |
| MaxTemp       | The maximum temperature in degrees celsius                                                                             |
| Rainfall      | The amount of rainfall recorded for the day in mm                                                                      |
| Evaporation   | The so-called Class A pan evaporation (mm) in the 24 hours to 9am                                                      |
| Sunshine      | The number of hours of bright sunshine in the day.                                                                     |
| WindGustDir   | The direction of the strongest wind gust in the 24 hours to midnight                                                   |
| WindGustSpeed | The speed (km/h) of the strongest wind gust in the 24 hours to midnight                                                |
| WindDir9am    | Direction of the wind at 9am                                                                                           |
| WindDir3pm    | Direction of the wind at 3pm                                                                                           |
| WindSpeed9am  | Wind speed (km/hr) averaged over 10 minutes prior to 9am                                                               |
| WindSpeed3pm  | Wind speed (km/hr) averaged over 10 minutes prior to 3pm                                                               |
| Humidity9am   | Humidity (percent) at 9am                                                                                              |
| Humidity3pm   | Humidity (percent) at 3pm                                                                                              |
| Pressure9am   | Atmospheric pressure (hpa) reduced to mean sea level at 9am                                                            |
| Pressure3pm   | Atmospheric pressure (hpa) reduced to mean sea level at 3pm                                                            |
| Cloud9am      | Fraction of sky obscured by cloud at 9am. This is measured in "oktas", which are a unit of eigths. It records how many |
| Cloud3pm      | Fraction of sky obscured by cloud (in "oktas": eighths) at 3pm. See Cload9am for a description of the values           |
| Temp9am       | Temperature (degrees C) at 9am                                                                                         |
| Temp3pm       | Temperature (degrees C) at 3pm                                                                                         |
| RainToday     | Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0                                       |
| RainTomorrow  | The amount of next day rain in mm. Used to create response variable RainTomorrow. A kind of measure of the "risk".     |

## objectives

**Graded Challenge 2** ini dibuat guna mengevaluasi konsep Logistic Regression dan SVM sebagai berikut:

- Mampu memahami konsep Classification dengan Logistic Regression dan SVM.
- Mampu mempersiapkan data untuk digunakan dalam model Logistic Regression dan SVM.
- Mampu mengimplementasikan Logistic Regression dan SVM untuk membuat prediksi.
