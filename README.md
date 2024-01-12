# ArmUbuntuEnv
Env setup in Ubuntu(ARM)

## TensorFlow-2.4.1(Python 3.7)

whl files [link](https://dedemaker-1255717351.cos.ap-nanjing.myqcloud.com/bilibili/TensorFlow-2.4.1.zip)

how to install [video link](https://www.bilibili.com/video/BV11a4y127Us/?vd_source=db13df6c5b0634a345593a5afaed3798)

## TensorFlow(multiple versions)
### Get tensorflow whl:

whl files [link](https://github.com/KumaTea/tensorflow-aarch64/releases)

### Install grpcio(grpcio-1.32.0 as example)

get source file from [link](https://pypi.org/project/grpcio)

```bash
wget -c https://files.pythonhosted.org/packages/0e/5f/eeb402746a65839acdec78b7e757635f5e446138cc1d68589dfa32cba593/grpcio-1.32.0.tar.gz
tar -zxvf grpcio-1.32.0.tar.gz 
cd grpcio-1.32.0
python3 setup.py install
```

### Install h5py(h5py-2.10.0 as example)

pip install cython==0.29.21

get source file from [link](https://pypi.org/project/h5py)

```bash
wget -c https://files.pythonhosted.org/packages/5f/97/a58afbcf40e8abecededd9512978b4e4915374e5b80049af082f49cebe9a/h5py-2.10.0.tar.gz
tar -zxvf h5py-2.10.0.tar.gz
cd h5py-2.10.0
python3 setup.py install
```

