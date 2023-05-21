# image_remix_python

Для запуска алгоритма потребуется:
1) Скачать репозиторий
2) Скачать модели по ссылке: https://drive.google.com/drive/folders/1SQDBt4YekymAVUmfnKmyXYtAM9UD-B1N?usp=sharing. Папки unet и vae необходимо сохранить в папке pretrained_model (pretrained_model/unet, pretrained_model/vae).
3) Установить зависимости: pip install -r requirements.txt

Инференс:
python run.py /path/to/content_image /path/to/style_image /path/to/output/image.png(jpg)
![1_content](https://github.com/Maestro2506/image_remix_python/assets/56483302/6da5701a-87ec-4064-9c48-117372e917c2)![1_style](https://github.com/Maestro2506/image_remix_python/assets/56483302/0eca746f-be74-49a4-8e16-1dc2f07232bb)
 ![remix_1](https://github.com/Maestro2506/image_remix_python/assets/56483302/9e8253c4-e0e3-47b8-9a37-fb800a3cc6ac)
 
 
![2_content](https://github.com/Maestro2506/image_remix_python/assets/56483302/98ecc497-e9cf-4f0e-b223-76dd3b2b3f54)![2_style](https://github.com/Maestro2506/image_remix_python/assets/56483302/9453c63c-f93d-4d5a-9c34-d1fdd9986cce)
![remix_2](https://github.com/Maestro2506/image_remix_python/assets/56483302/face3140-aa4d-4b38-a9f6-f751e4495592)


Данный ремикс основан на Stable Diffusion.
