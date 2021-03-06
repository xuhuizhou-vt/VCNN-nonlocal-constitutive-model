# VCNN - Vector Cloud Neural Network
The vector-cloud neural network (VCNN) is a promising tool not only as nonlocal constitutive models and but also as general surrogate models for PDEs on irregular domains. It is a frame-independent neural network, strictly invariant both to coordinate translation and rotation and to the ordering of points in the cloud. The network can deal with any number of arbitrarily arranged grid points and thus is suitable for unstructured meshes in fluid simulations.

Co-developed by Dr. Heng Xiao's group at Virginia Tech: [Data-Enabled Computational Mechanics Laboratory at Virgnia Tech](https://www.aoe.vt.edu/people/faculty/xiaoheng/personal-page.html) and Dr. Jiequn Han at Flatiron Institute: [Center for Computational Mathematics](https://users.flatironinstitute.org/~jhan/).

### VCNN for Scalar Transport
<div align=center><img width="966" src="https://github.com/xuhuizhou-vt/VCNN-nonlocal-constitutive-model/blob/master/figs/schematic-NN.png"/></div>

This repository contains the code and data for the following paper(s):

*   X-H. Zhou, J.Q. Han, and H. Xiao. Frame-independent vector-cloud neural network for nonlocal constitutive modelling on arbitrary grids. *Computer Methods in Applied Mechanics and Engineering* 388, 114211, 2021. DOI: [10.1016/j.cma.2021.114211](https://doi.org/10.1016/j.cma.2021.114211). Also available at arXiv: [https://arxiv.org/abs/2103.06685](https://arxiv.org/abs/2103.06685)

The current work is about scalar transport PDE. We are working on extending the VCNN to tensor transport PDE.

Contributors:
-------------
* Xu-Hui Zhou
* Jiequn Han
* Heng Xiao

Contact: Xu-Hui Zhou     
Email address: xuhuizhou@vt.edu
