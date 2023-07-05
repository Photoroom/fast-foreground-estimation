# Approximate Fast Foreground Colour Estimation
Official repository for the paper [Approximate Fast Foreground Colour Estimation](https://ieeexplore.ieee.org/document/9506164). ICIP 2021.
Awarded Best Industry paper.

<img src="./images/radius_slide_portrait.gif" style="float: center;" width="450" height="600">

Naively compositing without an estimate of foreground colour leads to bleed-through of the original background.   

In this work, we propose a foreground estimation technique. Our method can be implemented 11 lines of Python code and yields comparable results to the [full approach [1]](#References), while also being faster. 

* [Watch project video](https://youtu.be/ZQNJMLO4p8A)

![Teaser](./images/icip_2021_poster_image.png)

## API Usage
PhotoRoom includes foreground estimation by default in the [Backround Removal API](https://www.photoroom.com/api/), see [documentation](https://docs.photoroom.com/docs/api).

### Requirements
- numpy # For mathematical operations.
- opencv-python # Efficient blur implementation. 

## Citation

```
@INPROCEEDINGS{ApproxForegroundForte2021,
  author={Marco Forte},
  booktitle={2021 IEEE International Conference on Image Processing (ICIP)}, 
  title={Approximate Fast Foreground Colour Estimation}, 
  year={2021},
  doi={10.1109/ICIP42928.2021.9506164}}
```

## References
(1) [Fast Multi-Level Foreground Estimation](https://www.computer.org/csdl/proceedings-article/icpr/2021/09412408/1tmhtKdoleU)
