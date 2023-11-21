## Micro Frontend 
Micro frontend adalah pendekatan dalam pengembangan aplikasi web di mana antarmuka pengguna (UI) dibagi menjadi beberapa bagian independen yang dapat dikelola secara terpisah. Ide utamanya adalah mengadopsi prinsip mikroservis untuk frontend, di mana aplikasi web dibangun menggunakan beberapa bagian kecil yang terpisah, setiap bagian dapat dikembangkan, dikelola, dan dideploy secara independen.

Dalam arsitektur micro frontend, setiap bagian dari antarmuka pengguna dipecah menjadi unit-unit yang lebih kecil yang dapat berdiri sendiri. Bagian-bagian ini dapat berupa widget, komponen, atau modul kecil lainnya yang mewakili fungsionalitas atau bagian spesifik dari antarmuka pengguna.

### Teknologi yang digunakan
- Vue 3
- Vuex
- Yarn
- Webpack's 5 (Federation)

### Case: 
Project Company -> Host
Project Shop -> Remote

Project Company memiliki component Header. Component tersebut di expose oleh project company agar dapat digunakan / diremote oleh project lain. Dalam case ini project shop melakukan remote terhadap project company dan dapat menggunakan component yang berada pada Company kedalam Shop.

![image info](./micro-frontend-architecture.png)
