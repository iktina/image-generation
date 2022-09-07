# Neural Image Generation

## Welcome
The service receives a text and uses it as an input for a pre-trained model.

## What’s the point?
The service generates 3 images that correspond to the text using machine learning methods. The service receives a text string and outputs 3 images in binary format, representing generated images based on the received text. 

## How does it work?

This implementation assumes the use of one of two generation models at the user's choice `Min-Dalle` and `Stable Diffusion`.

The user must provide a `string of text` to create images based on this string and `select a model` to generate

The perimeter `type` is responsible for choosing the model. If this parameter is active (1), then the model `Min-Dalle` will work, if this parameter is not active (0), then the model `Stable Diffusion` will work.

Inputs:

* `metod`: image_generation
* `input_data`: a string containing the text for generation

## Expected result

> Text: rainy sunset

`Min-Dalle`

[![imageban](https://i5.imageban.ru/out/2022/09/07/3b42e780f2787036122ab687d2bc9106.png)](https://imageban.ru) [![imageban](https://i4.imageban.ru/out/2022/09/07/fcc831f0238e3dbc2bf4c25e9214f7a0.png)](https://imageban.ru) [![imageban](https://i4.imageban.ru/out/2022/09/07/4ce30a90387f4b5ef6ddb5e7ad662c4a.png)](https://imageban.ru)

`Stable Diffusion`

<img src="https://i3.imageban.ru/out/2022/09/07/8050ff464d2c1bb8cad7682d1a21c266.png" width="255" />  <img src="https://i2.imageban.ru/out/2022/09/07/c0dd88ad1ef05e129feb12550cb5d327.png" width="255" /> <img src="https://i5.imageban.ru/out/2022/09/07/4937a8ceb9dfde8810745d5505205b82.png" width="255" />
