# Batch processing scripts for gimp

*Do **not** use this without a backup. Each file in the working directory may be destroyed.*

*Usage*

```
$ gimp -i -b '(crop-and-make-transparent "*.png")' -b '(gimp-quit 0)'
```

**Example: crop-and-make-transparent**

![cat image](test/cat.png) vs. ![cropped cat image](test/cat_crop.png)
