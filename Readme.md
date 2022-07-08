




## :wrench: Dependencies and Download

- NVIDIA GPU + CUDA >=11.2
- Linux Ubuntu 20.05

### Download

We now provide a set of **user-friendly test procedures** and **test sets** used for experiments,
Include two sets of Real-world blurred image and eight sets of Synthetic blurred image.<br>

*Provided Documents Hierarchical Directory :* <br>

```
​```
# First
├──Readme.md/ 

# Second
├──Demo_help.mp4/  #Simple software usage demo

# Third
├──run_view/    #Display software package
  ├── run_view  #This is an exe file
  ├── ......
  
# Fourth
├──Test_Dataset/  #Experimental test set
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
​```
```

If you try to run the demo, you can follow the steps below.

1. Enter the View directory and run the run_view file

   ```bash
   cd run_view
   ./run_view
   ```

2. Choose dataset path<br>

   - Input Option: Blurred image path and The ground truth path.<br>

   - Output Option: Deblurred results save **root directory**.<br>

     Ps: The generated image will be saved in the automatically generated Deblurred directory.

     

     **Tips**  

     - Real-World do not have GT(the ground truth) image, so its GT path can be replaced by blurred image path.
     - You can view all deblurred images in the result save directory to avoid missing the display process.


