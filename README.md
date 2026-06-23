# ColorFuseNet-Dataset
Controllable Garment Image Generation

## Description
This dataset contains sketch, color guidance map, text description, 
and real garment image quadruples for controllable garment image generation.

## Structure
```
ColorFuseNet-Dataset/
├── README.md                  # 数据集介绍、字段说明、引用方式
├── LICENSE                     # 许可证文件（CC BY 4.0）
├── .gitattributes              # Git LFS 跟踪规则配置文件
└── data/
    ├── testA/                  # 测试集：草图 (sketch)
    ├── testB/                  # 测试集：真实服装图像 (real garment image)
    ├── test_color_guides/      # 测试集：色彩引导图 (color guidance map)
    ├── test_prompts/           # 测试集：文本描述 (text description)
    ├── trainA/                 # 训练集：草图 (sketch)
    ├── trainB/                 # 训练集：真实服装图像 (real garment image)
    ├── train_color_guides/     # 训练集：色彩引导图 (color guidance map)
    └── train_prompts/          # 训练集：文本描述 (text description)
```


## License
This dataset is released under CC BY 4.0.

## Citation
If you use this dataset, please cite:
ColorFuseNet: Hierarchical Priority-Guided Tri-Stream Diffusion for Controllable Garment Image Generation
## Google driver
https://drive.google.com/file/d/1oTJEozG2q2-MrdI8f1O3S01hMAsMmrMB/view?usp=drive_link
