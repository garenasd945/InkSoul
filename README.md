# InkSoul

This is the repository for Ink Soul system.



## Dataset

The dataset contains 766 images and corresponding keyword text labels, and we provide the download link for the dataset.

https://zenodo.org/records/14726929

## Model

We provide the trained LoRA model ChineseLandscapePainting.safetensors, and

![usage1](README.assets/usage1-17378166101721.png)

We input:

```html
<lora:ChineseLandscapePainting:1>,mountain,sunset,house
```

lora:ChineseLandscapePainting: 1 means calling our trained Chinese ink landscape painting LoRA model, setting DFG=3, and clicking the generate button.

System output:

![10](README.assets/10.jpg)



If we input:

```html
<lora:ChineseLandscapePainting:1>,mountain,river,fishing boat
```

setting DFG=3,

System output:

![11](README.assets/11.jpg)





