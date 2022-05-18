# SimpleYoloAug
a really simple wrapper over python imgaug for yolo datasets

需要将图片及对应的标注 `txt` 文件放在同一目录下

How to use

```
python ./simple_augment.py --indir your/images/path --outdir /your/output/path --gen amount_of_duplicates
```

Example 
```
python ./simple_augment.py --indir ~/images/ --outdir ~/gen_images/ --gen 10
```
