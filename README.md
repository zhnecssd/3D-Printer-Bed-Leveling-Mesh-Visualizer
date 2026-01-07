# 3D Printer Bed Leveling Mesh Visualizer
Ссылка на телеграм канал  с  информацией по 3д печати https://t.me/model3dfile  ,   ссылка на чат https://t.me/+Btd-N7ENMPVlYzFi . 

The description in English can be found below

Запустить онлайн / USE IT ONLINE https://huggingface.co/spaces/zhnecssd/3D_Printer_Bed_Leveling_Mesh_Visualizer 

Поддержка различных размеров сетки (от 2x2 до 10x10).

Инструмент для визуализации и анализа данных выравнивания стола 3D-принтера. Позволяет создавать 3D-визуализацию, тепловые карты и графики поперечного сечения на основе данных автоматического выравнивания стола.
![photo_2024-12-30_22-54-44](https://github.com/user-attachments/assets/1da983c8-45a6-4cb1-9978-69600b02c5f3)![photo_2024-12-30_22-54-40](https://github.com/user-attachments/assets/a8daa52b-23e8-485f-925d-5e55f470b0f6)


🚀 Возможности

3D визуализация поверхности стола.
Тепловая карта с отображением отклонений.
Графики поперечного сечения по осям X и Y.
Статистика и анализ перепадов высот.
Рекомендации по настройке Z-offset и параметров первого слоя.
Поддержка различных размеров сетки (от 2x2 до 10x10).

📋 Требования

Copypython >= 3.10.
streamlit.
numpy.
plotly.

🛠 Установка (если онлайн не устроило и захотелось запустить на ПК)

Установить python.
  Переходим на официальный сайт [https://www.python.org/downloads/](https://www.python.org/downloads/release/python-3128/) и жмем download (скачать). Сайт автоматически определит разрядность вашей операционной системы и предложит сохранить 32-bit, либо 64-bit версию.
  После скачивания дважды щелкните по файлу, чтобы запустить мастер установки Python.
  Add Python to PATH – добавит название в системную переменную, для быстрого и удобного ее вызова из командной строки одной командной (без нее пришлось бы каждый раз прописывать полный путь к исполняемому файлу).
  
Распаковываем архив.

📊 Использование

Скачать архив (жмем стрелку зеленой кнопки Code, Download ZIP)![photo_2024-12-30_23-27-06](https://github.com/user-attachments/assets/d2e3e8f9-0d80-4b56-a997-23fba5b1943a)
Открыть папку CBedLeveling.
Запустите run_app.bat.
После установки необходимых файлов запустится браузер с окном программы. 
Вставьте данные сетки в текстовое поле.
Нажмите кнопку "Визуализировать".

📈 Интерпретация результатов

Рекомендации по перепадам высот:
Перепады до 0.2 мм:
Нормальное состояние для современных принтеров.
Компенсируется автокалибровкой.

Перепады от 0.2 до 0.5 мм:
Требуют внимания.
Возможны проблемы с адгезией.
Рекомендуется корректировка настроек первого слоя.

Перепады от 0.5 до 1 мм:
Критический диапазон.
Высокий риск проблем с печатью.
Требуется механическая регулировка.

Перепады выше 1 мм:
Серьёзная проблема.
Необходима полная перенастройка стола.

📝 Лицензия
Распространяется под лицензией MIT. Смотрите LICENSE для получения дополнительной информации.

👨‍💻 Автор
Alexandr Kurilchik - @Alexandr_Alexandrovich_Kurilchic

🙏 Благодарности

Belop и cookiemonster- за помощь в тестировании и отзывы.

Изначально писалось для anycubic cobra 2 pro, но подходит для других 3д принтеров. 

Для получение точек высот стола anycubic cobra 2 pro и дальнейшей визуализации тепловой карты высот стола anycubic cobra 2 pro, прочтите "Инструкция anycubic cobra 2 pro.docx" в папке "anycubic cobra 2 pro".

ENG

# 3D Printer Bed Leveling Mesh Visualizer
Link to telegram channel with information on 3D printing https://t.me/model3dfile , link to chat https://t.me/+Btd-N7ENMPVlYzFi . 


Launch online https://huggingface.co/spaces/zhnecssd/3D_Printer_Bed_Leveling_Mesh_Visualizer 

Support for different mesh sizes (from 2x2 to 10x10).

A tool for visualising and analysing 3D printer table alignment data. Allows you to create 3D visualisations, heat maps and cross-sectional plots based on automatic table alignment data.
![photo_2024-12-30_22-54-44](https://github.com/user-attachments/assets/1da983c8-45a6-4cb1-9978-69600b02c5f3)![photo_2024-12-30_22-54-40](https://github.com/user-attachments/assets/a8daa52b-23e8-485f-925d-5e55f470b0f6)


🚀 Features

3D visualisation of the table surface.
Heat map with deviation display.
Cross-sectional plots in X and Y axes.
Statistics and analysis of height differences.
Recommendations for setting Z-offset and first layer parameters.
Support for different grid sizes (from 2x2 to 10x10).

📋 Requirements

Copypython >= 3.10.
streamlit.
numpy.
plotly.

🛠 Installation (if online is not satisfactory and you want to run on PC)

Install python.
  Go to the official website [https://www.python.org/downloads/](https://www.python.org/downloads/release/python-3128/) and click download. The site will automatically detect the bitness of your operating system and offer to save the 32-bit or 64-bit version.
  After downloading, double-click the file to run the Python installation wizard.
  Add Python to PATH - will add the name to a system variable, for quick and easy invocation from the command line (without it, you would have to write the full path to the executable every time).
  
Unpack the archive.

📊 Usage

Download the archive (click the green arrow Code button, Download ZIP)![photo_2024-12-30_23-27-06](https://github.com/user-attachments/assets/d2e3e8f9-0d80-4b56-a997-23fba5b1943a).
Open the CBedLeveling folder.
Run run_app.bat.
Once the necessary files are installed, a browser with a programme window will launch. 
Paste the grid data into the text box.
Click on the ‘Visualise’ button.

📈 Interpretation of the results

Recommendations for height differences:
Differences up to 0.2 mm:
Normal condition for modern printers.
Compensated by autocalibration.

Differences between 0.2 and 0.5 mm:
Requires attention.
Possible adhesion problems.
Adjustment of the first layer settings is recommended.

Gradients between 0.5 and 1 mm:
Critical range.
High risk of printing problems.
Mechanical adjustment is required.

Variations above 1 mm:
Serious problem.
A complete reconfiguration of the table is required.

📝 Licence
Distributed under the MIT licence. See LICENSE for more information.

👨‍💻 Author
Alexandr Kurilchik - @Alexandr_Alexandrovich_Kurilchic

🙏 Acknowledgements

Belop and cookiemonster- for help in testing and feedback.

Originally written for anycubic cobra 2 pro, but suitable for other 3d printers. 

To get anycubic cobra 2 pro table height points and further visualise anycubic cobra 2 pro table height heatmap, read ‘anycubic cobra 2 pro.docx instructions’ in the ‘anycubic cobra 2 pro’ folder.



Translated with DeepL.com 
