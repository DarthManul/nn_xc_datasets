# nn_xc_datasets

Данные сохранены в файле reactions.json

Пример:

    "w4_17": {
        "0": {
            "reaction_name": "TAE_W4-17_1",
            "energy": "677.8",
            "W4-17_acetaldehyde": "-1",
            "W4-17_c": "2",
            "W4-17_o": "1",
            "W4-17_h": "4"
        }
        }
        
w4-17 - название датасета

"0" - индекс реакции в данном датасете

"reaction_name"- название реакции (как у Певерати)

"energy" - энергия реакции (в ккал/моль)

Остальные данные сохранены в формате: (название .xyz-файла): (коэффициент в реакции)

Файлы геометрии расположены в папке "Geometries"

Помимо этого, в наличии есть csv файлы датасетов w4-17 и изменённого S66x8 (S66x7)

