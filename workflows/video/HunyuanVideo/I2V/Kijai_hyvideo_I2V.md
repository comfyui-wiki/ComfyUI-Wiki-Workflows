## Custom Nodes

You need to install the following custom nodes:

- [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) 
- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper)
- [ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)

If you don't know how to install custom nodes, please refer to the [ComfyUI Custom Nodes Installation Guide](https://comfyui-wiki.com/en/install/install-custom-nodes)

## Model Download

- [hunyuan_video_vae_bf16.safetensors](https://huggingface.co/Kijai/HunyuanVideo_comfy/blob/main/hunyuan_video_vae_bf16.safetensors) 

- [hunyuan_video_I2V_fp8_e4m3fn.safetensors](https://huggingface.co/Kijai/HunyuanVideo_comfy/blob/main/hunyuan_video_I2V_fp8_e4m3fn.safetensors)

After downloading, please organize the files as shown below and save them in the corresponding folders under `ComfyUI/models`

```
ComfyUI/
├── models/
│   ├── vae/
│   │   └── hunyuan_video_vae_bf16.safetensors
│   └── diffusion_models/
│       └── hunyuan_video_I2V_fp8_e4m3fn.safetensors
```
