# lab_1
Programming languages lab_1

Сервер слушает 8000 порт и работает с директорией, в которой он находится, и всеми ее поддиректориями.
Для просмотра файлов и папок текущей директории, нужно обратиться к ней через URL. Сервер вернет массив json объектов - папок и файлов текущей директории. Например localhost:8000/main или localhost:8000/main/1
Если обратиться подобным образом к файлу, то он будет скачан.
Для создания папок нужно использовать запрос с параметром createdir, значение которого будет являться именем новой папки, например localhost:8000/main?createdir=testfolder
Удаление папок с помощью запроса с параметром deletedir, значение которого будет являться именем удаляемой папки (удаляются только пустые папки), например localhost:8000/main?deletedir=testfolder
