# Predicción de patologías cardiacas de acuerdo a los métodos convolucionales usando características cinemáticas.
### Alejandra Moreno Tarazona - 2151841


Las enfermedades cardiovasculares son unas de las principales causas de muerte a nivel mundial. Según la asociación mundial de la salud (WHO) en el año 2016 se registraron al rededor de 17.9 Millones de muertes por estas causar y últimamente este número se ha ido incrementando con el paso del tiempo. Las enfermedades cardiovasculares pueden llegar a darse debido a la mala alimentación, estrés, manejo de la vida cotidiana y el sedentarismo. Según diversas fuentes, últimamente las personas menores de 30 años, han tenido incontables infartos agudos de miocardios por las razones anteriormente mencionadas.

Como metodología se planea clasificar de buena manera usando cinemáticas de movimiento tales como el flujo, la aceleración tangencial y la imágen en crudo, a estas plicarles deep features de una red convolucional del estado del arte, usar transfer learning y apoyarse en alguna arquitectura 3D convolusional. Por tanto, el objetivo de este proyecto es clasificar de una buena manera las enfermedades cardiovasculares y así brindarle una herramienta al doctor experto en el tema para que así el pueda determinar si un paciente tiene una patología cardiaca en específica.

El Dataset usado es el "SunnyBrook" propuesto en el challenge de MICCAI 2009. Consta de 45 pacientes, donde 32 son hombres y 13 son mujeres, cuatro patologías las cuales son, Falla cardiaca sin infarto(HF-NI), Falla cardiaca con infarto(HF-I), Hipertrofia(HYP) y pacientes en condición Normal (N). Con cada una de las imágenes de 256x256. Cabe aclarar que se obtuvo un slice predeterminado para la clasificación de patologías cardiacas escogido de forma manual.
