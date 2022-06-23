

## :wrench: Dependencies and Download
- NVIDIA GPU + CUDA >=11.2
- Linux Ubuntu 20.05

### Download
We now provide a **Deblurred Visualization Demo** and **test sets** used for experiments,
Include two sets of Real-world blurred image and eight sets of Synthetic blurred image.<br>

If you try to run the demo, you can follow the steps below.

1. Download Demo.zip and unzip it.

    ```bash
    git clone https://github.com/TencentARC/GFPGAN.git
    cd GFPGAN
    ```
    *Demo.zip Hierarchical directory*
    ```
    │Demo.zip/
    ├──View.zip/
      ├── run_view  #This is an exe file
      ├── ......
    ├──Dataset/
      ├── Real-World  #Each dataset includes a subfile of blur
         ├── real_img_al
         ├── real_img
      ├── Synthetic  #Each dataset includes two sub-files, blur and gt(The ground truth)
         ├── CelebA
         ├── CelebA_al
         ├── FFHQ
         ├── Helen
         ├── Helen_al
         ├── LFW
         ├── MultiPIE
         ├── VGGFace
    ```


2. Unzip View.zip and run the run_view file

    ```bash
    ./run_view
    ```

3. Choose dataset path<br>
   - Input Option: Blurred image path and The ground truth Path.<br>
   - Output Option: Deblurred results save path.<br><br>
   **Tips**  
      -  Real-World do not have GT(the ground truth) image, so its GT path can be replaced by blurred image path.
      -  You can view all deblurred images in the result save directory to avoid missing the display process.

