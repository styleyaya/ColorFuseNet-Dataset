# ColorFuseNet-Dataset
Controllable Garment Image Generation

## Description
This dataset contains sketch, color guidance map, text description, 
and real garment image quadruples for controllable garment image generation.

## Structure
ColorFuseNet-Dataset/
├── README.md              ← 数据集介绍、字段说明、引用方式
├── LICENSE                 ← 许可证文件（如CC BY 4.0）
├── data/
│    ├──testA:/sketch       
|    |——testB:/real garment image
|    |——test_color_guides:/color guidance map
|    |——test_prompts:/text description
|    |——trainA:/sketch       
|    |——trainB:/real garment image
|    |——train_color_guides:/color guidance map
|    |——train_prompts:/text description
|
└── .gitattributes          ← 如果用Git LFS需要这个文件


## License
This dataset is released under CC BY 4.0.

## Citation
If you use this dataset, please cite:
ColorFuseNet: Hierarchical Priority-Guided Tri-Stream Diffusion for Controllable Garment Image Generation
## Google driver
https://drive.google.com/file/d/1oTJEozG2q2-MrdI8f1O3S01hMAsMmrMB/view?usp=drive_link
