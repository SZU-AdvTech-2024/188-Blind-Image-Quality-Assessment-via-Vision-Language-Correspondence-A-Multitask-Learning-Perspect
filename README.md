# Requirement

torch 1.8+

torchvision

Python 3

pip install ftfy regex tqdm

pip install git+https://github.com/openai/CLIP.git

# Pre-trained weights

Google Drive: 

https://drive.google.com/file/d/1GoKwUKNR-rvX11QbKRN8MuBZw2hXKHGh/view?usp=sharing

百度网盘： 

链接: https://pan.baidu.com/s/1KHjj7T8y2H_eKE6w7HnWJA 提取码: 2b8v 

将下载的文件LIQE.pt放到checkpoints文件夹里面

# Demo

将demo.py中的img1和img2的值改为想要评价的图像路径，然后运行

```bash
python demo.py
```

# Training

```bash
python train_unique_clip_weight.py
```

# Evaluation

```bash
python BIQA_benchmark.py
```

