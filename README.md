# RLMason

install anaconda https://www.anaconda.com/
install unity https://unity3d.co
  check install dev tools "microsoft visual studio community2019" within installation

download https://github.com/Unity-Technologies/ml-agents
  version16
  unizip in c drive

anaconda promt admin
  conda create -n "name" python=3.7
  pip3 install torch~=1.7.1 -f https://download.pytorch.org/whl/torch_stable.html
  python -m pip install mlagents==0.25.1
  # check for versions in the mlagents documentation
  change to mlagents dir

create unity project 3D option
  edit->project settings->package manager->check enable preview packages, check show dependencies
  install ML Agents version according to Unity Package from mlagents documentation
