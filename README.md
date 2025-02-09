# HOW TO RUN

## Note:
After cloning this repository, add two folders which are present in the Google Drive link given below at the same level as the `update` folder.

Google Drive Link: https://drive.google.com/drive/folders/1HHx62UWiUbT804RlNL7j3bbGRtyWtl4b?usp=drive_link

## If you have an NVIDIA GPU:
Run:
```batch
run_nvidia_gpu.bat
```

## To run it in slow CPU mode:
Run:
```batch
run_cpu.bat
```

## If you get a red error in the UI:
Make sure you have a model/checkpoint in:
```
ComfyUI\models\checkpoints
```

You can download the Stable Diffusion 1.5 model and add these models at the path ComfyUI\models\checkpoints:
[Stable Diffusion 1.5 Checkpoint](https://huggingface.co/Comfy-Org/stable-diffusion-v1-5-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors)

## Recommended Way to Update:
To update the ComfyUI code, run:
```batch
update\update_comfyui.bat
```


## Application Screenshots

![Landing UI Page](ScreenShots/Screenshot1.png)
![Outout 1](ScreenShots/Screenshot2.png)
![Queue showing all Outputs](ScreenShots/Screenshot3.png)
