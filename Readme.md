

## :wrench: Dependencies and Download
- NVIDIA GPU + CUDA >=11.2
- Linux Ubuntu 20.05

### Download
We now provide a **Deblurred Visualization Demo** and **test sets** used for experiments,
Include two sets of Real-world blurred image and eight sets of Synthetic blurred image.<br>

If you try to run the demo, you can follow the steps below.

*Provided Documents Hierarchical Directory :* <br>

    ```
    # First
    ├──Demo_video.mp4/  #Simple software usage demo
    
    # Second
    ├──View.zip/    #Display software package
      ├── run_view  #This is an exe file
      ├── ......
      
    # Third
    ├──Dataset/  #Experimental test set
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
         
    # Fourth
    ├──Our_deblurred_results    #Our experimental results
      ├── Real-World  #Each dataset includes a subfile of Deblurred
         ├── real_img_al
         ├── real_img
      ├── Synthetic  #Each dataset includes a subfile of Deblurred
         ├── CelebA
         ├── CelebA_al
         ├── FFHQ
         ├── Helen
         ├── Helen_al
         ├── LFW
         ├── MultiPIE
         ├── VGGFace
    ```

1. Download View.zip and unzip it.<br>
   *Download Link :* <br>
        [View.zip](https://drive.google.com/file/d/1LMhYlDkUfzMvxOrEOzPgsiWtRYT02flT/view?)<br>
        [Dataset](https://drive.google.com/drive/folders/1ppUgxn4UiaSkyxAxWOcq1dFgtHlFGQsr?usp=sharing)<br>
        (Option)[Demo_video.mp4](https://drive.google.com/file/d/1GECMpzvoW5zc04g2GWii7PcYVLLuilb_/view?usp=sharing)<br>
        (Option)[Our_deblurred_results](https://drive.google.com/drive/folders/1UZJhhYVfBJlXRiKT2Q37BMYQoUsk2p59?usp=sharing)<br>

    ```bash
    unzip View.zip
    ```
 
2. Enter the View directory and run the run_view file

    ```bash
    cd View
    ./run_view
    ```
    
3. Choose dataset path<br>
   - Input Option: Blurred image path and The ground truth path.<br>
   - Output Option: Deblurred results save path.<br><br>
   **Tips**  
      -  Real-World do not have GT(the ground truth) image, so its GT path can be replaced by blurred image path.
      -  You can view all deblurred images in the result save directory to avoid missing the display process.

