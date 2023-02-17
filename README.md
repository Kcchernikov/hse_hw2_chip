# hse_hw2_chip

[Collab](https://colab.research.google.com/drive/1EV-V9AvrOw6iohn0feaNrfpxXzI8QUeV?usp=sharing)

Для исследования была выбрана клеточная линия SK-N-SH и гистоновая метка H3K9me3.

## Анализ FastQC

1-ая ChipSeq реплика: ENCFF002ABI

<img width="540" alt="image" src="https://user-images.githubusercontent.com/80039707/219706232-530ea598-529e-4dfe-9fa9-798accbf2d15.png">
<img width="860" alt="image" src="https://user-images.githubusercontent.com/80039707/219706264-6ad44808-9941-4325-81c2-2c4a7fdbe264.png">
<img width="871" alt="image" src="https://user-images.githubusercontent.com/80039707/219706392-abbf027b-99e1-4aa1-868a-176682fde8eb.png">
<img width="867" alt="image" src="https://user-images.githubusercontent.com/80039707/219706505-84918647-2bfe-456d-9a6c-9acdb98176f7.png">

2-ая ChipSeq реплика: ENCFF002ABJ

<img width="573" alt="image" src="https://user-images.githubusercontent.com/80039707/219706616-4c862454-251f-4cbd-a7c5-0ccc38c7459d.png">
<img width="866" alt="image" src="https://user-images.githubusercontent.com/80039707/219706668-5b603380-bd0e-418c-b507-fdfe230fe28b.png">
<img width="890" alt="image" src="https://user-images.githubusercontent.com/80039707/219706871-231f368c-28b9-46f6-8e8a-17a6d5447b22.png">
<img width="851" alt="image" src="https://user-images.githubusercontent.com/80039707/219706730-d80182de-7bbb-4c93-b603-3b3a18b64119.png">

Контроль: ENCFF002ABO

<img width="536" alt="image" src="https://user-images.githubusercontent.com/80039707/219707071-bca645ad-16e3-4db4-9d20-a013bd2ec565.png">
<img width="871" alt="image" src="https://user-images.githubusercontent.com/80039707/219707102-9ac114d0-fae7-4aaa-84e2-355562286fc3.png">
<img width="884" alt="image" src="https://user-images.githubusercontent.com/80039707/219707138-3b377950-c767-4744-87a5-1c99fed316f4.png">
<img width="860" alt="image" src="https://user-images.githubusercontent.com/80039707/219707176-3e43e228-a0ce-4628-ab08-e2c9344c92c5.png">

Подрезание не потребовалось, качество ридов хорошее.

Таблица со статистикой по выравниванию на 15 хромосому

<img width="1394" alt="image" src="https://user-images.githubusercontent.com/80039707/219707585-e17713bc-11ee-4226-ab74-76ee4ea838b6.png">
Процент выравниваний и получился таким низким, потому что выравнивание производилось лишь на 1 хромосому

## Диаграммы Эйлера-Венна

Пересечение пиков 1 реплики и ENCODE
<img width="878" alt="image" src="https://user-images.githubusercontent.com/80039707/219707910-9c84d609-9e42-4ba7-981b-7fde6d8bbc4a.png">
<img width="853" alt="image" src="https://user-images.githubusercontent.com/80039707/219708054-c96676e0-3fb2-4867-84ab-5374d3ac9b46.png">

Пересечение пиков 2 реплики и ENCODE
<img width="854" alt="image" src="https://user-images.githubusercontent.com/80039707/219708123-e20f3a3f-dc41-4613-ad30-5a5b4090d33d.png">
<img width="848" alt="image" src="https://user-images.githubusercontent.com/80039707/219708202-c5b7f9f1-9ccf-4969-b9dc-b907430dbd34.png">

Пересечений довольно мало из-за того, что выравнивание производилось только на одну хромосому.
