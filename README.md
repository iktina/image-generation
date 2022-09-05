# Neural Image Generation

## Welcome
The service receives a text and uses it as an input for a pre-trained model.

## What’s the point?
The service generates 3 images that correspond to the text using machine learning methods. The service receives a text string and outputs 3 images in binary format, representing generated images based on the received text. 

## How does it work?

This implementation assumes the use of one of two generation models at the user's choice `Min-Dalle` and `Stable Diffusion`.

The user must provide a `string of text` to create images based on this string and `select a model` to generate

## Expected result

> Text: koala holding an orange

`Min-Dalle`

[![imageban](https://i3.imageban.ru/out/2022/09/05/89621a4e2d4b15d9efcb4bc23284481e.png)](https://imageban.ru) [![imageban](https://i2.imageban.ru/out/2022/09/05/0540e42402c1b2b1ec60a2aa49a585a4.png)](https://imageban.ru) [![imageban](https://i4.imageban.ru/out/2022/09/05/2c56d99b5e99ab7ff9797e95828c91c2.png)](https://imageban.ru)

`Stable Diffusion`

<img src="https://i1.imageban.ru/out/2022/09/05/55af50eaa68e0ea2063878dc40469bc3.png" width="250" />  <img src="https://i6.imageban.ru/out/2022/09/05/47cb78e8caad76dedae14e0b822029c1.png" width="250" /> <img src="https://i1.imageban.ru/out/2022/09/05/0846425d1036846642ddf16b171c14fe.png" width="250" />
