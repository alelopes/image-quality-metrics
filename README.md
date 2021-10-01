# New Image Quality Metrics

Metrics used here:

FLIP: https://github.com/NVlabs/flip.git

LPIPS: https://github.com/richzhang/PerceptualSimilarity.git

Download Both and put in your folder (not gonna provide recursive linking here


## Running

There is a conda env available for this step, if you think its useful (although the projects don't have many dependencies)


#### Flip

Enter flip repo folder and python folder

python flip.py --reference <png_image_path> --test <png_image_path>

LOWER IS BETTER


#### LPIPS

with gpu:
python lpips_2imgs.py -p0 <reference_png_image_path> -p1 <new_png_image_path> --use_gpu

without gpu:
python lpips_2imgs.py -p0 <reference_png_image_path> -p1 <new_png_image_path>


LOWER IS BETTER
