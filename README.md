# EG3D: Efficient Geometry-aware 3D Generative Adversarial Networks<br><sub>Official PyTorch implementation</sub>

![Teaser image](./docs/teaser.jpg)

**Efficient Geometry-aware 3D Generative Adversarial Networks**<br>
Eric R. Chan*, Connor Z. Lin*, Matthew A. Chan*, Koki Nagano*, Boxiao Pan, Shalini De Mello, Orazio Gallo, Leonidas Guibas, Jonathan Tremblay, Sameh Khamis, Tero Karras, and Gordon Wetzstein<br>*\* equal contribution*<br>
<br>
https://matthew-a-chan.github.io/EG3D<br>

Abstract: *Unsupervised generation of high-quality multi-view-consistent images and 3D shapes using only collections of single-view 2D photographs has been a long-standing challenge. Existing 3D GANs are either compute-intensive or make approximations that are not 3D-consistent; the former limits quality and resolution of the generated images and the latter adversely affects multi-view consistency and shape quality. In this work, we improve the computational efficiency and image quality of 3D GANs without overly relying on these approximations. For this purpose, we introduce an expressive hybrid explicit-implicit network architecture that, together with other design choices, synthesizes not only high-resolution multi-view-consistent images in real time but also produces high-quality 3D geometry. By decoupling feature generation and neural rendering, our framework is able to leverage state-of-the-art 2D CNN generators, such as StyleGAN2, and inherit their efficiency and expressiveness. We demonstrate state-of-the-art 3D-aware synthesis with FFHQ and AFHQ Cats, among other experiments.*

## Citation

```
@inproceedings{Chan2021,
  author = {Eric R. Chan and Connor Z. Lin and Matthew A. Chan and Koki Nagano and Boxiao Pan and Shalini De Mello and Orazio Gallo and Leonidas Guibas and Jonathan Tremblay and Sameh Khamis and Tero Karras and Gordon Wetzstein},
  title = {Efficient Geometry-aware {3D} Generative Adversarial Networks},
  booktitle = {arXiv},
  year = {2021}
}
```

## Acknowledgements

We thank David Luebke, Jan Kautz, Jaewoo Seo, Jonathan Granskog, Simon Yuen, Alex Evans, Stan Birchfield, Alexander Bergman, and Joy Hsu for reviewing early drafts and for the helpful suggestions and feedback. We thank Alex Chan, Giap Nguyen, and Trevor Chan for help with figures and diagrams. Koki Nagano and Eric Chan were partially supported by DARPA’s Semantic Forensics (SemaFor) contract (HR0011-20-3-0005). The views and conclusions contained in this document are those of the authors and should not be interpreted as representing the official policies, either expressed or implied, of the U.S. Government. Distribution Statement "A" (Approved for Public Release, Distribution Unlimited).
