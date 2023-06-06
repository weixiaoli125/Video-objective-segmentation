## Video-objective-segmentation

***Segmentation Anything***  is a state-of-the-art computer vision technique (https://github.com/facebookresearch/segment-anything) that involves the process of dividing an image into multiple segments or regions based on certain criteria. 

***Track-Anything*** is a flexible and interactive tool (https://github.com/gaomingqi/Track-Anything) for video object tracking and segmentation. Users can modify the objects they wish to track or update the region of interest in case of any ambiguities during tracking.

<div align=center>
<img src="./assets/avengers.gif" width="81%"/>
</div>

<!-- ![avengers]() -->


## :world_map: Video Tutorials 

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

