# RNCryptor
RNCryptor加密解密Python代码

####**Dependencies** 
/assets/pycrypto-2.6.1.tar.gz
```bash
tar -zxvf /assets/pycrypto-2.6.1.tar.gz
sudo python setup.py install
```

####**用法**
```bash
python RNCryptor.py
```

```python
cryptor = RNCryptor()
#加密
cryptor.encrypt(Data,password)
#解密
cryptor.decrypt(Data,password)
```


![](assets/markdown-img-paste-20180802133443449.png)
