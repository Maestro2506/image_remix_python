# image_remix_python

Для запуска алгоритма потребуется:
1) Скачать репозиторий
2) Скачать модели по ссылке: https://drive.google.com/drive/folders/1SQDBt4YekymAVUmfnKmyXYtAM9UD-B1N?usp=sharing. Папки unet и vae необходимо сохранить в папке pretrained_model (pretrained_model/unet, pretrained_model/vae).
3) Установить зависимости для проекта: pip install -r requirements.txt

Инференс:
python run.py /path/to/content_image.png /path/to/style_image.png /path/to/output/image.png(jpg)

Данный ремикс основан на Stable Diffusion.
