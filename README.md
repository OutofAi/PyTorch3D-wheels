<img src="https://visitor-badge.laobi.icu/badge?page_id=OutofAi/PyTorch3D-wheels">
This repository facilitates the creation of Python wheel files (.whl) from the Pytorch-3D project to streamline the installation process on Google Colab 


For L4 GPU
```
!curl -L "https://github.com/OutofAi/PyTorch3D-wheels/releases/download/0.7.8/pytorch3d-0.7.8.postAda260124-cp311-cp311-linux_x86_64.whl" -o pytorch3d-0.7.8-cp311-cp311-linux_x86_64.whl
!pip install pytorch3d-0.7.8-cp311-cp311-linux_x86_64.whl --force-reinstall
import pytorch3d
```

For A100 GPU
```
!curl -L "https://github.com/OutofAi/PyTorch3D-wheels/releases/download/0.7.8/pytorch3d-0.7.8.postAmpere260124-cp311-cp311-linux_x86_64.whl" -o pytorch3d-0.7.8-cp311-cp311-linux_x86_64.whl
!pip install pytorch3d-0.7.8-cp311-cp311-linux_x86_64.whl --force-reinstall
import pytorch3d
```

For Huggingface Spaces add this to your requirements.txt
```
pytorch3d @ https://github.com/OutofAi/PyTorch3D-wheels/releases/download/0.7.8/pytorch3d-0.7.8.postHopper271126-cp310-cp310-linux_x86_64.whl
```
