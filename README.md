# Python_PQAES_FO

# FOR UBUNTU 18.04 (SIBC DOESN'T RUN, ONLY PQAES Quantum Safe AES and Fujisaki-Okamoto Transform only run)

## Installing all dependencies

```
apt-get install python3-pip wget
```
```
apt-get install python3-pip
```
```
pip3 install progressbar
```
```
pip3 uninstall numpy
```
```
pip3 install "numpy<1.20.0"
```
```
pip3 install click
```
```
pip3 install progress
```
```
pip3 install sympy
```
```
apt-get install git
```

## TESTING AES PQAES AND FO ON SYMMETRIC KEY
```
wget https://github.com/SitrakaResearchAndPOC/Python_PQAES_FO.git
```
```
cd ..
```
```
git clone https://github.com/SitrakaResearchAndPOC/Python_PQAES_FO.git
```
```
cd Python_PQAES_FO/
```
```
unzip Python-PQAES.zip 
```
```
cd Python-PQAES
```
```
cd Python-PQAES-CSIDH/
```
```
python3 AES.py 
```
```
python3 -e test.txt -c 128
```
```
python3 AES.py -e test.txt -c 128
```
```
python3 AES.py -e test.txt -c 128
```
```
python3 AES.py -d test.txt.aes -c 128
```
```
gedit test_dec.txt 
```
```
tail -f test_dec.txt
```
```
tail -f test.txt
```
```
python3 FO.py 
```
```
python3 FO.py -e test.txt -a sha256 -k 1235
```
```
python3 FO.py 
```
```
ls
```
```
python3 FO.py -e test.txt -a sha256 -k bob.priv 
```
```
python3 FO.py -d test.txt.fo -a sha256 -k bob.priv 
```
```
tail f test_fo.txt 
```

# FOR UBUNTU 20.04 (RUN CORRECTLY FOR ALL)
