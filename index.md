## Contact Info
**Office**: 
3345 MEB<br/>
School of Computing <br/>
University of Utah<br/>
USA<br/>

**E-mail** : milinda (at) cs (dot) utah (dot) edu

You can find my CV [here](cv/build/milinda_cv.pdf)

## About Me

I am a Ph.D. (in scientific computing track) student at School of Computing, University of Utah. I did my undergraduate studies in the field of Computer Science at University of Moratuwa. Currently, I am working as a Graduate Research Assistant, under 
<a href="http://www.cs.utah.edu/~hari/" target="_blank">Prof. Hari Sundar </a>


My research is focused on, developing scalable parallel algorithms to solve Partial Differential Equations (PDEs), Galerkin methods (both continous & discontinous), finite differences & fintie volume methods based on octree based adaptive discritizations

## Education
* 2015-present : Univeristy of Utah, Ph.D Scientific Computing 
* 2010-2015 : University of Moratuwa, B.Sc Computer Science

<!--- <a href="" target="_blank"></a> ---> 

## Research

### Computational Relativity

<a href="https://github.com/paralab/Dendro-GR" target="_blank">Dendro-GR</a> : Massivly parallel computational framework for computational general relativity (<a href="https://arxiv.org/abs/1807.06128" target="_blank">arXiv:1807.06128v1</a>). 

<video width="400" height="225" controls loop>
   <source src="./vids/r1_U_CHI.mp4" type="video/mp4">
   Your browser does not support the video tag.
  </video>
  
  ```
  Equal mass ratio binary compact merger, slice over the octree of BSSN variable chi variable
  ```

   <video width="400" height="225" controls loop>
   <source src="./vids/r1_chi.mp4" type="video/mp4">
   Your browser does not support the video tag.
   </video>
   
   ```
   Equal mass ratio binary compact merger, slice over the octree of BSSN variable chi variable  
   with refinement. 
   ```

### Non-Linear Sigma Model

Simple non-linear wave equation solved by Dendro-GR to demonstrate the Wavelet Adaptive Mesh Refinement (WAMR)

<video width="400" height="225" controls loop>
 <source src="./vids/lwaveEq.mp4" type="video/mp4">
 Your browser does not support the video tag.
</video>

```
Linear wave equation solved using RK4 time stepper using Dendro-GR. Note how the refinement captures  
the propergation of the wave. 
```



<video width="400" height="225" controls loop>
 <source src="./vids/nlsmB.mp4" type="video/mp4">
 Your browser does not support the video tag.
</video>

```
Non linear wave equation with two Gaussian distributions as the initial condition.
```

### Space Filling Curve based octree partitioning. 

Hilbert curve based octree partitioning
![Communication graph for Hilbert curve based partitioing for finite element matvec](./figs/hilbert_with_threshold_0p1.png)

Morton curve based octree partitioning
![Communication graph for Morton curve based partitioing for finite element matvec](./figs/morton_with_threshold_0p1.png)



## Publications
For full publication list please visit my <a href="https://scholar.google.com/citations?user=PPKkq2cAAAAJ&hl=en" target="_blank">Google Schoolar</a> page, here are some of the selected publications.

1. Milinda Fernando, David Neilsen, Hyun Lim,  Eric Hirschmann, Hari Sundar, "Massively Parallel Simulations of Binary Black Hole Intermediate-Mass-Ratio Inspirals" (<a href="https://arxiv.org/abs/1807.06128" target="_blank">arXiv:1807.06128v1</a> ) (Submited to SIAM SISC journal)

2. Milinda Fernando, Dmitry Duplyakin, and Hari Sundar. 2017. Machine and Application Aware Partitioning for Adaptive Mesh Refinement Applications. In Proceedings of the 26th International Symposium on High-Performance Parallel and Distributed Computing (HPDC '17). ACM, New York, NY, USA, 231-242. 

3. Isuru Fernando, Sanath Jayasena, Milinda Fernando, Hari Sundar, "A Scalable Hierarchical Semi-Separable Library for Heterogeneous Clusters" 2017 46th International Conference on Parallel Processing (ICPP), Bristol, UK, 2017

4. Jayasena, S.; Fernando, M.; Rusira, T.; Perera, C.; Philips, C., "Auto-Tuning the Java Virtual Machine," in Parallel and Distributed Processing Symposium Workshop (IPDPSW), 2015 IEEE International , vol., no., pp.1261-1270, 25-29 May 2015 doi: 10.1109/IPDPSW.2015.84
