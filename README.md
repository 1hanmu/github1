# github1
conda create --name animated_drawings python=3.8.13
conda activate animated_drawings

git clone https://github.com/facebookresearch/AnimatedDrawings.git
cd AnimatedDrawings
pip install -e .

~ % conda activate animated_drawings
(animated_drawings) ~ % cd {location of AnimatedDrawings on your computer}
(animated_drawings) AnimatedDrawings % python
from animated_drawings import render
render.start('./examples/config/mvc/interactive_window_example.yaml')
