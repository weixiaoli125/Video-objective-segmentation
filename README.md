

***Track-Anything*** is a flexible and interactive tool for video object tracking and segmentation. It is developed upon [Segment Anything](https://github.com/facebookresearch/segment-anything), can specify anything to track and segment via user clicks only. During tracking, users can flexibly change the objects they wanna track or correct the region of interest if there are any ambiguities. These characteristics enable ***Track-Anything*** to be suitable for: 
- Video object tracking and segmentation with shot changes. 
- Visualized development and data annotation for video object tracking and segmentation.
- Object-centric downstream video tasks, such as video inpainting and editing. 

<div align=center>
<img src="./assets/avengers.gif" width="81%"/>
</div>

<!-- ![avengers]() -->


## :world_map: Video Tutorials ([Track-Anything Tutorials in Steps](./doc/tutorials.md))

https://user-images.githubusercontent.com/30309970/234902447-a4c59718-fcfe-443a-bd18-2f3f775cfc13.mp4



## :computer: Get Started
#### Linux & Windows
```shell
# Clone the repository:
git clone https://github.com/gaomingqi/Track-Anything.git
cd Track-Anything

# Install dependencies: 
pip install -r requirements.txt

# Run the Track-Anything gradio demo.
python app.py --device cuda:0
# python app.py --device cuda:0 --sam_model_type vit_b # for lower memory usage
```


## :book: Citation
If you find this work useful for your research or applications, please cite using this BibTeX:
```bibtex
@misc{yang2023track,
      title={Track Anything: Segment Anything Meets Videos}, 
      author={Jinyu Yang and Mingqi Gao and Zhe Li and Shang Gao and Fangjing Wang and Feng Zheng},
      year={2023},
      eprint={2304.11968},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

