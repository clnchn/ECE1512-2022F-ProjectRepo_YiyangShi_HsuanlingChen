# ECE1512-2022F-ProjectRepo_YiyangShi_HsuanlingChen
This github repository contains the Project A for ECE1512 Digital Image Processing by Yiyang Shi and HsuanLing Chen. 

##About the project
In this project, we will be focusing on the setting of knowledge distillation as a model compression technique and to explore the practicality of transfer knowledge from a larger model to a smaller one in real-world settings. There are two parts of the project, 
(1)using conventional knowledge distillation framework as a model compression method for a digit classification dataset, “MNIST” 
(2)use of transfer learning and knowledge distillation to train a lightweight model for mimicking a pre-trained model from the clinical histopathology dataset, “MHIST”

Experimental Setup – What you need
1. Prerequisites:
(a) Python 3.X
(b) Sci-kit-learn (suggested)
(c) NumPy (suggested) (d) Matplotlib (suggested)

GPU Requirements
Note that you do not need a GPU to successfully complete Project A. You should be able to train your models on your local (personal) machines. However, if you so wish, you can use a GPU by accessing Google Colab. Following are the steps to enable a GPU using Colab:
1. Upload the code base to Colab using your Google Drive.
2. Navigate to Runtime → Change runtime type in the top bar.
3. Change runtime accelerator to GPU and click Save.
4. Use device = torch.device(”cuda:0”) after importing libraries and call .to(device) function to trans- fer your model and tensors to GPU. Make sure that model and tensor both are placed on GPU.
