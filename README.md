# dav-university-1

# git clone https://github.com/intel/intel-extension-for-transformers.git

Cloning into 'intel-extension-for-transformers.gited.... 
Username for 'https://github.com": "C

# conda create -n itrex python-3.10 - I

Retrieving package metadata: ...working... done
Channels:
  - defaults
Platform: linux-64

Package Plan:
  environment location: /home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/1trex-1

  added/updated specs:
    - python=3.10

The following NEW packages will be INSTALLED:

  ld_impl_linux-64  pkgs/main/linux-64::ld_impl_linux-64-2.38-h1181459_1
  libgcc-ng        pkgs/main/linux-64::libgcc-ng-11.2.0-h1234567_1
  libstdcxx-ng     pkgs/main/linux-64::libstdcxx-ng-11.2.0-h1234567_1
  libuuid          pkgs/main/linux-64::libuuid-1.41.5-h5eee18b_
  ncurses          pkgs/main/linux-64::ncurses-6.4-h6a678d5_@
  openssl          pkgs/main/linux-64::openssl-3.0.14-h5eee18b_0
  python           pkgs/main/linux-64::python-3.10.14-h955ad1f_1
  readline         pkgs/main/linux-64::readline-8.2-h5eee18b_0
  setuptools       pkgs/main/linux-64::setuptools-69.5.1-py310h06a4308_0
  sqlite           pkgs/main/linux-64::sqlite-3.45.3-h5eee18b_0
  tk               pkgs/main/linux-64::tk-8.6.14-h39e8969_0
  tzdata           pkgs/main/noarch::tzdata-20248-he4d1e81_0
  wheel            pkgs/main/linux-64::wheel-0.43.0-py310h06a4308_0
  xz               pkgs/main/linux-64::xz-5.4.6-h5eee18b_1
  zlib             pkgs/main/linux-64::zlib-1.2.13-h5eee18b_1

  Additional Packages:
  - bzip2            pkgs/main/linux-64::bzip2-1.0.8-h5eee186_6
  - ca-certificates  pkgs/main/linux-64::ca-certificates-2024.3.11-h06a4308_0
  - libffi           pkgs/main/linux-64::libffi-3.4.4-h6a678d5_1
  - pip              pkgs/main/linux-64::pip-24.0-py310h06a4308_0
  - zlib             pkgs/main/linux-64::zlib-1.2.13-h5eee18b_1

Preparing transaction: ...working... done
Verifying transaction: ...working... done
Executing transaction: ...working... done

#To activate this environment, use
 $ conda activate itrex-1
 #
#To deactivate an active environment, use
$conda deactivate

# conda activate itrex

uc820865aa685ee277c4ba3d82c0528d@idc-training-gpu-compute-24:~$ conda activate 1trex-1
(1trex-1) 
# pip install intel-extension-for-transformers

Using cached intel_extension_for_transformers-1.4.2-cp310-cp316-manylinux_2_28_x66_64.hl.metadata (26 kB) Collecting packaging (from intel-extension-for-transformers)
Using cached packaging-24.1-py3-none-any hl.metadata (3.2 kB)
Collecting numpy (from intel-extension-for-transformers)
Using cached numpy-2.0.0-ep210-cp318-many linux_2_17_86_64 many linux 2014 x86_64.uhl.metadata (68 kB) Collecting schers (from intel-extension-for-transformers)
Using cached schema-0.7.7-py2.py3-none-any.whl metadata (34 kB)
Collecting pyyaml (from Intel-extension-for-transformers)
Using cached PyYAM-6.0.1-cp310-cp316-manylinux_2_17_x86_64.many linux2014 x86_64.h1.netadate (2.1 kB) Collecting neural-compressor (from intel-extension-for-transformers)
Using cached neural compressor-2.6-py3-none-any.wh1.metadata (15 kB)
Collecting transformers (from Intel-extension-for-transformers)
Using cached transformers-4.41.2-py3-none-any.whl metadata (43 kB)
Collecting deprecated -1.2.13 (from neoral-compressor-intel-extension for transformers)
Using cached Deprecated-1.2.14-py2.py3-none-any.wh1.netadata (5.4 kB)
Collecting numpy (from Intel-extension-for-transformers)
Using cached numpy-1.26.4-cp310-cp310-menylinux_2_17_x86_64.many linux2014_x86_64.hl.metadata (61 kB)
Collecting opencv-python-headless (from neural compressor-intel-extension-For-transformers)
Using cached opencv_python_headless-4.10.0.34-cp37-ab13-manylinux_2_17_x86_64.manylinux2014_x86_64.hl.metadata (20 KB) Collecting pandas (from neural-compressor->intel-extension-for-transformers)
Using cached pandas-2.2.2-cp310-cp310-many linux 2.17 x86-64,manylinux2014_x86_64.whi.eetedats (19 kB)
Collecting Pillow (from neural-compressor->intel-extension-for-transformers)
Using cached pillow-10.3.0-cp310-cp310-manylinux_2_28_x86_64.ahl.metadata (9.2 kB)
Collecting prettytable (from neural-compressor->intel-extension-for-transformers)
Using cached prettytable-3.18.0-py3-none-any.whl metadats (36 kn)
Collecting psutil (from neural-compressor intel-extension-for-transformers)
Using cached psuti1-6.0.0-cp36-ab13-manylinux_2_12_x86_64.manylinux2010_x86_64 many linux_2_17_x86_64.many 11nux2014 x86_64.h1.metadata (21 (5) Collecting py-cpuinfo (from neural-compressor->Intel-extension-for-transformers)
Using cached py_cpuinfo-9.0.0-py3-none-any.whl.metadata (794 bytes)
Collecting requests (from neural-compressor-intel-extension-for-transformers)
Using cached requests-2.32.3-py3-none-any-whl.metadata (4.6 KB)
Collecting scikit-learn (from neural-compressor-intel-extension-for-transformers)
Using cached scikit learn-1.5.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1.metadata (11 KB) Collecting pycocotools (from neural-compressor-intel-extension-for-transformers)
Using cached pycocotools-2.0.8-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.hl.metadata (1.1 kB) Collecting filelock (from transformers-intel-extension-for-transformers)
Using cached filelock-3.15.3-py3-none-any.whi.metadata (2.9 kB)
Collecting huggingface-hub-1.0,0.23.0 (from transformers intel extension-for-transformers)
Using cached hugging face_hub-0.23.4-py3-none-any.whl eetadata (12 kB)
Collecting regexi-2019.12.17 (from transformers->intel-extension-for-transformers)
Using cached regex-2624.3.15-cp310-cp318-menylinux_2_17_x86_64 wenylinux2014_x86_64.hl, metadats (48 kB) Collecting tokenizers<0.20, -8.19 (from transformers intel-extension for transformers)


Collecting py-cpuinfo (From neural-compressor intel-extension-for-transformers) Using cached py_cpuinfo-9.0.0-py3-none-any.whl metadata (794 bytes) Collecting requests (from neural-compressor-intel-extension-for-transformers) Using cached requests-2.32.3-py3-none-any.whl.metadata (4.6 kB)
Collecting scikit-learn (from neural-compressor-intel-extension-for-transformers)
Using cached scikit learn-1.5,0-cp318-cp310-menylinux_2_17_x86_64.manylinux2014_x86_64.whi.metadata (11 kB) Collecting pycocotools (from neural-compressor->intel-extension-for-transformers)
Using cached pycocotools-2.8.0-cp318-cp310-manylinux_2_17_x86_64.many linux2014_x86_64.h1.metadata
Collecting filelock (from transformers intel-extension-fon-transformers)
Using cached filelotk-3.15.3-py3-none-any.whi-wetadata (2.9 kB]
Collecting fuggingtact-hunt1.8, 0.28.6-from-transformers->Intel-extension-for-transformer)
Using cached huggingface hus-0,23,4-py3-none-any ahl nafadats 12
Collecting regex-2016.12.17 (From, transformers-intel-extension-for-transfonders
(1:1 kB)
Using cached negex-2024.5.15-cp310-cp310-menylinux 2 17x86_64.many11nux2014_x86_64.hl.metadata (40 kB) Collecting rokenizers 8.20,-8.18 (from transformers-intel-extension-for-transtormers)
Using cached tokenizers 8.15.1-cp310-cp310-manylinux_2_17_x86_64.many linux2014_x86_64.hi.metadata (6.7 48) Collecting safetensors>-8.4,1 (from transformers-intel-extension-for-transformers)
Using cached safetensers-0.8.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.h1.metadata (3.8 kB)
Collecting cafea4, 27 (from transformers-intel-extension-for-transformers)
Using cached tqdm-4.66.4-py3-none-any.wal.metadata (57 58)
Collecting wrapt 2,1.18 (from deprecatedi-1.2.13-neural-compresson-intel-extension-for-transformers)
Using cached rape-1.16.8-cp310-cp318-manylinux 25 x86_64 many linux1 x86_64.many1inux 2 17 x86 64.many11nux2814_x86_64.h1.metadata (6.6 KB) Collecting fsspecs-2011.1.0 (from hugging face-hubice, -8.23-ransformers-intel-extensionsforetransformers)
Using cached Fespec-2024,6,8-py3-none-any instadata (14 kB)
Collecting typing extensions 3.74 (from huggingface-but-1.0,0.25.6-transformers-intel-extension-for-tronsformers) Using cached typing extensions-4.42.2-py3-one-aby.ubi meratata 3.2 kB)
Collecting sysbag-oxtensils 3.3.2 (from pandas-neural-cambres-intel-excensfor-for-transformers:
Using cached python datensit-2.0.8.post-py2.prengne angol metadet [8.4 kB
Collecting pytan2020:1 from pandas-spearel-compressar-intel sextension-fon-transformers
Using cached pytz-2824-1-py2.py3-none-any-wmL.meadete (22)
Collecting detasa2022, 7 (from pandas->neural-compressor->intel-extension-for-transformers)
Using cached data-2024.1-py2.py3-none-any-shimetadata (1)
Collecting width (from prettytable-neural-compressor->intel-extension-for-transformers)
Using cached ucidth-822.13-py2.py3-none-any.whl.metadata (14 kB)
Collecting matplotlib-2.1.0 (Fran pycneatsals-neurs-compressor-intel-extension-for-transformers)
Using cached matplotlib 3.9.0-spa10-pale-manylinux_2_17_x86_64.many linux2014_S8_64, wh1.metadata (118) Collecting charset normalizer(4,2 (from requests-neural-compressor->istel-extension-for-transformers)
Using cached chapiet normalizer-3.3.2-cp310-cp310-manvilux 2 17 x86_64.menylinu2014_x86_64.hl.detadata (33) Collecting dec42.5 from requests-neural-compressor-sintel-extension-for-transforeens)
Using cached Edna-8.7-py3-none-any metadata: (919 ke
Collecting urllib343-121.1 (from requests neural compressor-intel extension for transformers: Using cached uel11b3-2.2.2-py3-none-any.whl metadata (6.4 y
Collecting reititia2017.4117 (from requests->neural-compressor->intel-extension-for-transformers) Using cached certifi-2024.6.py3-none-anyuhl.metadeto (2.2 ke
Collecting scipy1.60 (from scikit-leananenral compressor Intel extension-for-transformers) Using cached scipy-1.13.1-cp310-cp318-manylinin 2 17 x86 6.manylinux291_x86_64.hetadata (60 (5) Collecting solib-1.3.8 (from scikit-learn-neural-compressor-intel-extension-for-transformers) Using cached jabib-1.4.1-py3-nosp-any.whjaetadata: 15.4 kB]
Collecting threadpoolctie.1. (from scikit-learn-neural compressor intel extension-for-transformers) Using cached thraadbully.5.8-pp-nuse-anyametadata: 13
Collecting threaoppy?4.1.1 feu notpiotiin 2.1.0-seycobsteals-seural-compresson-sintel-extension-for-transformers) Using cached contadepy-1-2.3-cpdie-ep310-manylimus_2_17_86_64.many linux2014_x86_64.nl.netadata (5,8 k)


Collecting fonttools-4.22.0 (from matplotlib-2.1.0-pycocotools->neural-compressor-intel-extension-for-transformers) Using cached fonttools-4.53.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.h1.metadata (162 kB) Collecting kiwisolver-1.3.1 (from matplotlib>=2.1.0-pycocotools->neural-compressor-intel-extension-for-transformers) Using cached kiwisolver-1.4.5-cp310-cp310-many linux_2_12_x86_64.many linux2010_x86_64.wh1.metadata (5.4 kB) Collecting pyparsing -2.3.1 (from matplotlib-2.1.0-pycocotools->neural-compressor-intel-extension-for-transformers) Using cached pyparsing-3.1.2-py3-none-any.wh1.metadata (5.1 kB)
Collecting six>=1.5 (from python-dateutils-2.8.2-pandss-neural-compressor->intel-extension-for-transformers) Using cached six-1.16.0-py2.py3-none-any.whl.metadata (1.8 kB)
Using cached intel_extension_for_transformers-1.4.2-cp310-cp310-manylinux_2_28_x86_64.whl (45.3 MB)
Using cached neural compressor-2.6-py3-none-any.whl (1.5 MB)
Using cached numpy-1.26.4-cp310-cp310-menylinux_2_17_x86_64.many linux2014 x86_64.whl (18.2 MB)
Using cached packaging-24.1-py3-none-any.whl (53 kB)
Using cached PyYANL-6.8.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (785 KB) Using cached schema-0.7.7-py2.py3-none-any.wh1 (18 kB)
Using cached transformers-4.41.2-py3-none-any.whl (9.1 MB)
Using cached Deprecated-1.2.14-py2.py3-none-any.whl (9.6 kB)
Using cached huggingface_hub-0.23.4-py3-none-any.whl (482 kB)
Using cached regex-2024.5.15-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (775 KB) Using cached safetensors-8.4.3-cp316-cp316-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.2 MB) Using cached tokenizers-0.19.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.6 MB) Using cached tqdm-4.66.4-py3-none-any.wh1 (78 kB)
Using cached filelock-3.15.3-py3-none-any.whl (16 kB)
Using cached opencv_python_headless-4.10.0.84-cp37-abi3-many linux_2_17_x86_64.manylinux2014 x86_64.whl (49.9 MB)
Using cached pandas-2.2.2-cp310-cp310-many linux_2_17_x86_64.many linux2014_x86_64.whl (13.0 MB)
Using cached pillow-10.3.0-cp310-cp310-manylinux_2_28_x86_64,wh1 (4.5 MB)
Using cached prettytable-3.10.0-py3-none-any.whl (28 kB)
Using cached psutil-6.0.0-cp36-abi3-menylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (290 kB) Using cached py_cpuinfo-9.0.0-py3-none-any.wh1 (22 kB)
Using cached pycocotools-2.0.8-cp316-cp310-many linux_2_17_x86_64.manylinux2014_x86_64.whl (427 kB)
Using cached requests-2.32.3-py3-none-any.wh1 (64 kB)
Using cached scikit learn-1.5.0-cp310-cp310-menylinux_2_17_x86_64.many linux2014 x86_64.hl (13.3 MB) Using cached certifi-2024.6.2-py3-none-any.whl (164 ks)
Using cached charset_normalizer-3.3.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2814_x86_64.wh1 (142 kB) Using cached fsspec-2024.6.0-py3-none-any.whl (176 KB)
Using cached idne-3.7-py3-none-any.whl (66 kB)
Using cached joblib-1.4.2-py3-none-any.wh1 (301 ks)
Using cached matplotlib-3.9.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64,wh1 (8,3 MB)
Using cached python_dateutil-2.9.0.poste-py2.py3-none-any.whl (229 kB)
Using cached pytz-2024.1-py2.py3-none-any.whl (505
kB)
(38.
Using cached scipy-1.13.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (38.5 MB)
Using cached threadpoolct1-3.5.0-py3-none-any.wh1 (18 kB)
Using cached typing extensions-4.12.2-py3-none-any.whl (37 kB)
Using cached tzdate-2024.1-py2.py3-none-any.whl (345 kB)
Using cached urllib3-2.2.2-py3-none-any.whl (121 kB)
Using cached wrapt-1.16.0-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (80 kB) Using cached wcwidth-0.2.13-py2.py3-none-any.wh1 (34 kB)
Using cached contourpy-1.2.1-cp310-cp310-many linux_2_17_x86_64.manylinux2014 x86_64.h1 (385 k6)
Using cached cycler-0.12.1-py3-none-any.whl (8.3 kB)
Using cached fonttools-4.53.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (4.6 MB)
Using cached kivisolver-1.4.5-cp310-cp310-manylinux_2_12_x86_64.manylinux2010_x86_64.whl (1.6 MB) Using cached pyparsing-3.1.2-py3-none-any.whl (103 kB)
Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Using cached filelock-3.15.3-py3-none-any.wh1 (16 kB)
Using cached opencv_python_headless-4.10.0.84-cp37-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (49.9 MB) Using cached pandas-2.2.2-cp310-cp316-manylinux_2_17_x86_64.many linux2014 x86_64.whl (13.0 MB)
Using cached pillow-10.3.0-cp310-cp310-manylinux_2_28_x86_64.wh1 (4.5 MB)
Using cached prettytable-3.10.0-py3-none-any.whl (28 kB)
Using cached psutil-6.0.0-cp36-abi3-manylinux_2_12_x86_64.manylinux2010_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (298 kB) Using cached py_cpuinfo-9.0.0-py3-none-any.wh1 (22 kB)
Using cached pycocotools-2.0.8-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (427 kB)
Using cached requests-2.32.3-py3-none-any.wh1 (64 kB)
Using cached scikit learn-1.5.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (13.3 MB)
Using cached certifi-2024.6.2-py3-none-any.whl (164 ks)
Using cached charset_normalizer-3.3.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (142 kB)
Using cached fsspec-2024.6.0-py3-none-any.whl (176 kB)
Using cached idna-3.7-py3-none-any.whl (66 kB)
Using cached joblib-1.4.2-py3-none-any.whl (301 ks)
Using cached matplotlib-3.9.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (8.3 MB)
Using cached python_dateutil-2.9.0.poste-py2.py3-none-any.wh1 (229 kB)
Using cached pytz-2024.1-py2.py3-none-any.whl (505 kB)
Using cached scipy-1.13.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (38.6 MB)
Using cached threadpoolct1-3.5.0-py3-none-any.whl (18 kB)
Using cached typing extensions-4.12.2-py3-none-any.whl (37 kB)
Using cached tzdata-2024.1-py2.py3-none-any.whl (345 kB)
Using cached urllib3-2.2.2-py3-none-any.wh1 (121 kB)
Using cached wrapt-1.16.0-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64,manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (80 kB) Using cached wcwidth-0.2.13-py2.py3-none-any.whl (34 kB)
Using cached contourpy-1.2.1-cp310-cp310-menylinux_2_17_x86_64.manylinux2014_x86_64.whl (305 kB)
Using cached cycler-0.12.1-py3-none-any.whl (8.3 kB)
Using cached fonttools-4.53.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (4.6 MB) Using cached kiwisolver-1.4.5-cp310-cp310-manylinux_2_12_x86_64.manylinux2010_x86_64.whl (1.6 MB) Using cached pyparsing-3.1.2-py3-none-any.whl (103 kB)
Using cached six-1.16.0-py2.py3-none-any.wh1 (11 kB)
Installing collected packages: wcwidth, schema, pytz, py-cpuinfo, wrapt, urllib3, tzdata, typing-extensions, tqdm, threadpoolctl, six, safetensors, regex, pyyaml, pyparsing, psutil, pret tytable, Pillow, packaging, numpy, kiwisolver, joblib, idna, fsspec, fonttools, filelock, cycler, charset-normalizer, certifi, scipy, requests, python-dateutil, opencv-python-headless, d eprecated, contourpy, scikit-learn, pandas, matplotlib, huggingface-hub, tokenizers, pycocotools, transformers, neural-compressor, intel-extension-for-transformers Successfully installed Pillow-10.3.0 certifi-2024.6.2 charset-normalizer-3.3.2 contourpy-1.2.1 cycler-0.12.1 deprecated-1.2.14 file lock-3.15.3 fonttools-4.53.0 fsspec-2024.6.0 huggingfac e-hub-0.23.4 idna-3.7 intel-extension-for-transformers-1.4.2 joblib-1.4.2 kiwisolver-1.4.5 matplotlib-3.9.0 neural-compressor-2.6 numpy-1.26.4 opencv-python-headless-4.10.0.84 packaging- 24.1 pandas-2.2.2 prettytable-3.10.0 psutil-6.0.0 py-cpuinfo-9.0.0 pycocotools-2.0.8 pyparsing-3.1.2 python-dateutil-2.9.0.poste pytz-2024.1 pyyaml-6.0.1 regex-2024.5.15 requests-2.32.3 safetensors-0.4.3 schema-0.7.7 scikit-learn-1.5.0 scipy-1.13.1 six-1.16.0 threadpoolct1-3.5.0 tokenizers-0.19.1 tqdm-4.66.4 transformers-4.41.2 typing-extensions-4.12.2 tzdata-2824.1 url lib3-2.2.2 wewidth-0.2.13 wrapt-1.16.0
Successfully installed intel-extension-for-transformers-0.1.0

# cd /intel-extension-for-transformers/intel_extension_for_transformers/neural_chat/

(1trex-1) uc820865aa685ee277c4ba3d82c0528d@idc-training-gpu-compute-24:/intel-extension-for-transformers/intel_extension_for_transformers/neural_chat$

# pip install -r requirements_cpu.txt


Looking in Indexes: https://pypi.org/simple, https://pytorch-extension, Intel.com/release-whl/stable/cpu/us/ Collecting accelerate=0.28.0 (from -r requirements_cpu.txt (line 2))
Using cached accelerate-0.28.0-py3-none-any.wh1.metadata (18 kB)
Collecting cchardet (from -r requirements_cpu.txt (line 3)) Using cached cchardet-2.1.7-cp310-cp310-linux_x86_64.whl Collecting einops (from -r requirements cpu.txt (line 4)) Using cached einops-0.8.0-py3-none-any.whi.metadata (12 kB) Collecting evaluate (from -r requirements_cpu.txt (line 5)) Using cached evaluate-0.4.2-py3-none-any.wh1.metadata (9.3 kB) Collecting fastapi (from -r requirements_cpu.txt (line 6)) Using cached fastapi-0.111.0-py3-none-any.whl.metadata (25 kB) Collecting fschat--0.2.32 (from -r requirements_cpu.txt (line 7)) Using cached fschat-8.2.32-py3-none-any.wh1.metadata (20 kB)
Requirement already satisfied: huggingface hub in /home/u9281ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from -r requirements_cpu.txt (line 8)) (0.23.4) Collecting intel_extension_for_pytorch=-2.3.8 (from -r requirements_cpu.txt (line 9))
Using cached https://intel-extension-for-pytorch.s3.amazonaws.com/ipex_stable/cpu/./intel_extension_for_pytorch-2.3.28cpu-cp318-cp310-linux_x86_64.wh1 (98,3 MB)
Requirement already satisfied: prettytable in /home/u9281ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from neural-compressor-> requirements_cpu.txt (li ne 11)) (3.10.0) Requirement already satisfied: py-cpuinfo. in /home/u9201ce8c8e7c885602fa7241-b=2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from neural-compressor->- requirements_cpu.txt (lin e 111) (9.0.0) Requirement already satisfied: schema in /home/u9281ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from neural-compressor-r requirements_cpu.txt (line 11 )) (0.7.7) Requirement already satisfied: pycocotools in /home/u9201ce8c87c085602fa7241be2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from neural-compressor->-r requirements cpu.txt (li ne 11)) (2.0.8) Collecting colocedlogs (from optimum requirements_cpu.txt (line 15))
Using cached coloreologs-15.6.1-py2.py3-none-any.whl metadata (12)
Collecting sentencepiece (from optimum-intel-- requirements cpu.txt (line 16))
Using cached sentencepiece-8.2.0-cp)10-cp310-sonylinux 2.17 x86_64 many linux2014_x86_64.whi.metadata 17.7 kB)
Requirement already satisfied: setuptools in /home/u9201ce8c8a7c0556e2fa7241be2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from optimum-Intel- requirements_cpu.txt (line 16 JJ (69.5-1)) Requirement already satisfied: selpy in /home/u8201ce3c8e7c0856027241be2550/.conda/envs/strex-2/14b/python3.10/site-packages (tras optinum-Intel-x-r requirements cpu.txt (line 16)) 19 13.19. Collecting onnx (from optimum intel- r requirements cpultxt (line 16))
Using cached onnx-1.16, 1-cp310-cp318-many14nox 17 x86_64 manylinux2014_x86_64.hl.metadata (16 kB) Collecting absl-py (frop rauge score-s-n requirements cpu.txt (line 21)) Using cached anal_py-2.1.0-py3-none-any.whl.metadata (2.3.8)
Collecting eltk (from rouge score->-r requirements cpu.txt (line 21)) Using cached nitk-3.8.1-py3-none-any.wh1.metadata (2.8 KB)
Requirement already satisfied: six=1:14.8 in /home/u9201ce8c8e7c085682fa7241be2550/.conda/envs/itrex-1/lib/python3. 10/site-packages (from rouge score-- requirements cpu.xxt (line 211 ) (1.16.0)
Collecting click (from sacremoses > requirements cpu.txt (line 22))
Using cached click-6.1.7-py3-none-any.wh1.metadata (3.0 kB)
Requirement already satisfied: joblib in /home/u9281ce8c8e7c065682f67241be2556/.conda/envs/itrex-1/lib/python3.18/site-packages (from sacremases--n requirements spu.txt (line 22)) (1-4 -2) Collecting anyio 5, 3.4.6 (from starletter requirements cou.txt (line 24))
Using cached anyLo-4.4.0-py3-none-any.whl.metadata (4,6 kB)
Requirement already satisfied: tokenizers36.20, 0.49 in /home/u9201ce6c8e7c085602fa7241ete2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from transformers-4.35.2-> requiremen ts_cpu.txt (line 28)) (0.19,1) Collecting h11-8.8 (from uvicom->- requirements_cpu.txt (line 38))
Using cached ht1-0.14.0-py3-none-any.whl metadata (8.2 KB)
Requirement already satisfied: idnes-2.8 in /home/u9281ce8c8e7c085602f87241be2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from shylax5, 3.4.8-5starletter requirements_cpu. txt (line 24)) (3.7) Collecting sniffio-1.1 (from anyio<5>3.4.0->starlette->r requirements_cpu.txt (line 24))
Using cached sniffic-1.3.1-py3-none-any.wh1.metadata (3.9 kB)
Collecting exceptiongup-1.0.2.(from anyies, 3.4.0->starletter requirements cpu.txt (line 24))
Using cached exceptiongroup 1:2.1-py3-none-any.wh.metadata (6.6 KB)
Collecting pyarrow>-15.0.0 (from astasets+2.0.0 evaluator requirements cou.txt (line 5)) Using cached pyarrow-16.1.0-2p310-cp320-many linux 2 28 x86_64:1.metadata (3.0 kB)
Collecting pyarrow-hotfix (from datasets-2.0.0-evaluate->r requirements cpu.txt (line 5))
Using cached pyarrow_hotfix-0.6-py3-none-any.whi.todate 13.6 81
Collecting fsspec from torch-2.3.0- requirements_cpu.txt (line 26))
Using cached fsspec-2024.5.0-py3-none-anya1.metadata (11 KB)
Requirement already satisfied: wrapt 2,0-1.18. in /home/u9281ce8c8e7c055682fa7241-be2558/.conda/envs/trex-1/lib/python3.18/site-packages (from deprecated-1.2.13-neural-compressor-y- equirements cpu.txt (line 11)7 (1.16.0) Collecting dnspython-2.0.8 (from email_validator-2.0.0-fastapi- requirements cpu.txt (line 6))
Using cached dnspython-2.6.1-py3-none-any.wh1.metadata (5.8 KB)
Collecting type>-8.12.3 (from fastapi-cli-0.8.2->fastapi->-r requirements cpu.txt (line 5))
Using cached typer 6, 12.3-py3-none-any.whi.metadata: (15 kB)


pu.txt (line 5)) (2.9.0.poste)
Requirement already satisfied: pytz>=2020.1 in /home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from pandas->evaluate->-r requirements_cpu.txt (li ne 5)) (2024.1) Requirement already satisfied: tzdata>-2022.7 in /home/u9281ce8c8e7c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from pandas->evaluate->-r requirements_cpu.txt ( line 5)) (2024.1)
Requirement already satisfied: matplotlib>=2.1.0 in /home/u9281ce8c8e7c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from pycocotools->neural-compressor->-r requi rements_cpu.txt (line 11)) (3.9.0)
Collecting DataProperty<2,>-1.0.1 (from pytablewriter->lm-eval->-r requirements_cpu.txt (line 10)) Using cached DataProperty-1.0.1-py3-none-any.wh1.metadata (11 kB)
Collecting abstrdecoder<2,>=1.0.0 (from pytablewriter->lm-eval->-r requirements_cpu.txt (line 10)) Using cached abstrdecoder-1.1.3-py3-none-any.wh1.metadata (4.0 kB)
Collecting pathvalidate<4, -2.3.0 (from pytablewriter->Im-eval->-r requirements_cpu.txt (line 10)) Using cached pathvalidate-3.2.0-py3-none-any.wh1.metadata (11 kB)
Collecting tabledata<2,>=1.3.1 (from pytablewriter->lm-eval->-r requirements_cpu.txt (line 10)) Using cached tabledata-1.3.3-py3-none-any.wh1.metadata (3.7 kB)
Collecting tcolorpy<1,>-0.0.5 (from pytablewriter->lm-eval->-r requirements_cpu.txt (line 10))
Using cached tcolorpy-0.1.6-py3-none-any.wh1.metadata (6.4 KB)
Collecting typepy<2,>=1.3.2 (from typepy [datetime] <2,>=1.3.2->pytablewriter->lm-evel->-r requirements_cpu.txt (line 10))
Using cached typepy-1.3.2-py3-none-any.whl.metadata (9.3 kB)
Collecting mpmath<1.4.8,-1.1.8 (from sympy->torch--2.3.0->-r requirements_cpu.txt (line 26))
Using cached mpmath-1.3.0-py3-none-any.wh1.metadata (8.6 kB)
Collecting edurl=0.1 (from markdown-it-py>=2.2.0->rich>=10.0.0->fschat =0.2.32->-r requirements_cpu.txt (line 7))
Using cached mdur1-0.1.2-py3-none-any.wh1.metadata (1.6 kB)
Requirement already satisfied: contourpy>-1.0.1 in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib>-2.1.0->pycocotools->neural-co mpressor->-r requirements_cpu.txt (line 11)) (1.2.1)
Requirement already satisfied: cycler>=0.10 in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib>=2.1.0->pycocotools->neural-compre ssor->r requirements_cpu.txt (line 11)) (0.12.1)
Requirement already satisfied: fonttools>-4.22.0 in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib>-2.1.8->pycocotools->neural-c ompressor->r requirements_cpu.txt (line 11)) (4.53.0)
Requirement already satisfied: kiwisolver>=1.3.1 in /home/u9281ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib>=2.1.0->pycocotools->neural-c ompressor->-r requirements_cpu.txt (line 11)) (1.4.5)
Requirement already satisfied: pyparsing -2.3.1 in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib>-2.1.0-pycocotools->neural-co mpressor->-r requirements_cpu.txt (line 11)) (3.1.2) Collecting chardet <6,>=3.0.4 (from mbstrdecoder<2,>=1.0.0->pytablewriter->lm-eval->-r requirements_cpu.txt (line 10))
Using cached chardet-5.2.0-py3-none-any.wh1.metadata (3.4 kB)
Collecting shellingham>-1.3.0 (from typer>-0.12.3->fastapi-cli>-0.0.2->fastapi->-r requirements_cpu.txt (line 6))
Using cached shellingham-1.5.4-py2.py3-none-any.whl.metadata (3.5 kB)
Collecting svgwrite (from wavedrom->markdown2 [all]->fschat--0.2.32->-r requirements_cpu.txt (line 7))
Using cached svgwrite-1.4.3-py3-none-any.wh1.metadata (8.8 kB)
Using cached accelerate-0.28.0-py3-none-any.wh1 (290 kB)
Using cached fschat-0.2.32-py3-none-any.wh1 (211 kB)
Using cached neural_speed-1.0a0-cp310-cp310-manylinux_2_28_x86_64.whl (23.1 MB)
Using cached numpy-1.23.5-cp310-cp310-manylinux_2_17_x86_64.many linux2014_x86_64.whl (17.1 MB)
Using cached peft-0.6.2-py3-none-any.whl (174 kB)
Using cached pydantic-1.10.13-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.1 MB) Using cached tiktoken-0.4.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.7 MB) Using cached torch-2.3.0-cp310-cp310-manylinux1_x86_64.wh1 (779.1 MB)


Using cached accelerate-0.28.0-py3-none-any.wh1 (290 kB) Using cached fschat-0.2.32-py3-none-any.wh1 (211 kB)
linux2014_x86_64.whl (17.1 MB)
Using cached neural speed-1.0a0-cp310-cp310-manylinux_2_28_x86_64.whl (23.1 MB) Using cached numpy-1.23.5-cp310-cp310-manylinux_2_17_x86_64.many Using cached peft-0.6.2-py3-none-any.whl (174 kB)
(3.1 MB)
Using cached pydantic-1.18.13-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 Using cached tiktoken-0.4.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.7 MB) Using cached torch-2.3.0-cp310-cp310-menylinux1_x86_64.whl (779.1 MB) Using cached torchaudio-2.3.0-cp310-cp310-manylinuxl_x86_64.h1 (3.3 MB) Using cached nvidia_cublas_cu12-12.1.3.1-py3-none-many linux1_x86_64.whl (410.6 MB) Using cached nvidia_cuda_cupti cu12-12.1.105-py3-none-manylinux1_x86_64.wh1 (14.1 MB) Using cached nvidia_cuda_nurtc_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (23.7 MB) Using cached nvidia_cuda_runtime
cu12-12.1.105-py3-none-manylinux1_x86_64.wh1 (823 kB) Using cached nvidia_cudnn_cu12-8.9.2.26-py3-none-manylinux1_x86_64.wh1 (731.7 MB) Using cached nvidia_cufft_cu12-11.0.2.54-py3-none-manylinux1_x86_64.whl (121.6 MB) Using cached nvidia_curand_cu12-18.3.2.106-py3-none-manylinux1_x86_64.whl (56.5 MB) Using cached nvidia_cusolver_cu12-11.4.5.107-py3-none-many linux1_x86_64.h1 (124.2 MB)


Using cached pathvalidate-3.2.0-py3-none-any.wh1 (23 kB)
Using cached protobuf-5.27.1-cp38-ab13-manylinux2014_x86_64.whl (309 kB) Using cached pyarrow-16.1.0-cp310-cp318-manylinux_2_28_x86_64.whl (40.8 MB) Using cached pygments-2.18.0-py3-none-any.wh1 (1.2 MB) Using cached sniffio-1.3.1-py3-none-any.wh1 (10 kB) Using cached tabledata-1.3.3-py3-none-any.whl (11 kB) Using cached tabulate-0.9.0-py3-none-any.whl (35 kB) Using cached tcolorpy-0.1.6-py3-none-any.whl (8.1 kB) Using cached typepy-1.3.2-py3-none-any.wh1 (31 kB) Using cached typer-0.12.3-py3-none-any.whl (47 kB)
Using cached uvloop-0.19.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (3.4 MB)
Using cached watchfiles-0.22.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (1.2 MB)
Using cached websockets-12.0-cp310-cp310-manylinux_2_5_x86_64.manylinux1_x86_64.manylinux_2_17_x86_64.manylinux2014_x86_64.whl (130 kB)
Using cached yarl-1.9.4-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (301 kB)
Using cached colorama-8.4.6-py2.py3-none-any.wh1 (25 kB)
Using cached 1xm1-5.2.2-cp310-cp310-manylinux_2_28_x86_64.wh1 (5.0 MB)
Using cached markdown2-2.4.13-py2.py3-none-any.whl (41 kB)
Using cached nvidia_nvjitlink_cu12-12.5.40-py3-none-manylinux2014_x86_64.wh1 (21.3 MB)
Using cached portalocker-2.8.2-py3-none-any.whl (17 kB)
Using cached pyarrow_hotfix-0.6-py3-none-any.wh1 (7.9 kB) Using cached chardet-5.2.0-py3-none-any.wh1 (199 kB) Using cached mdur1-0.1.2-py3-none-any.whl (10.0 KB) Using cached shellingham-1.5.4-py2.py3-none-any.whl (9.8 kB) Using cached svgwrite-1.4.3-py3-none-any.whl (67 kB)
Installing collected packages: word2number, sqlitedict, sentencepiece, oneccl_bind_pt, nh3, mpmath, cchardet, zstandard, yacs, xxhash, websockets, uvloop, ujson, triton, tcolorpy, tabula te, sympy, svgwrite, sniffio, shortuuid, shellingham, python-multipart, python-dotenv, pygments, pydantic, pybind11, pyarrow-hotfix, protobuf, prompt-toolkit, portalocker, pathvalidate, orjson, nvidia-nvtx-cu12, nvidia-nvjitlink-cu12, nvidia-nccl-cu12, nvidia-curand-cu12, nvidia-cufft-cu12, nvidia-cuda-runtime-cu12, nvidia-cude-nvrtc-cu12, nvidia-cuda-cupti-cu12, nvidia -cublas-cu12, numpy, neural speed, networkx, multidict, more-itertools, mdurl, MarkupSafe, markdown2, 1xml, humanfriendly, httptools, h11, fsspec, frozenlist, exceptiongroup, einops, dns python, dill, colorama, click, chardet, attrs, async-timeout, absl-py, yarl, wavedrom, uvicorn, tqdm-multiprocess, tiktoken, sacremoses, sacrebleu, pyarrow, onnx, nvidia-cusparse-cu12, n vidia-cudnn-cu12, numexpr, nltk, multiprocess, mbstrdecoder, markdown-it-py, jsonlines, jinja2, intel_extension_for_pytorch, httpcore, email_validator, coloredlogs, anyio, aiosignal, wat chfiles, typepy, starlette, rouge_score, rich, nvidia-cusolver-cu12, httpx, aiohttp, typer, torch, transformers_stream_generator, torchaudio, fastapi-cli, datasets, DataProperty, acceler ate, tabledata, peft, optimum, fastapi, evaluate, pytablewriter, optimum-intel, fschat, 1m-eval
Attempting uninstall: numpy
Found existing installation: numpy 1.26.4
Uninstalling numpy-1.26.4:
Successfully uninstalled numpy-1.26.4
Attempting uninstall: fsspec
Found existing installation: fsspec 2024.6.0 Uninstalling fsspec-2024.6.0:
Successfully uninstalled fsspec-2024.6.0
Successfully installed DataProperty-1.0.1 MarkupSafe-2.1.5 absl-py-2.1.0 accelerate-0.28.0 aiohttp-3.9.5 aiosignal-1.3.1 anyio-4.4.0 async-timeout-4.0.3 attrs-23.2.0 cchardet-2.1.7 chard et-5.2.0 click-8.1.7 colorama-0.4.6 coloredlogs-15.0.1 datasets-2.20.0 dill-0.3.8 dnspython-2.6.1 einops-0.8.0 email_validator-2.2.0 evaluate-0.4.2 exceptiongroup-1.2.1 fastapi-0.111.0 f astapi-cli-0.0.4 frozenlist-1.4.1 fschat-0.2.32 fsspec-2024.5.0 h11-0.14.0 httpcore-1.0.5 httptools-0.6.1 httpx-0.27.0 humanfriendly-10.0 intel_extension_for_pytorch-2.3.0+cpu jinja2-3.1 .4 jsonlines-4.0.0 1m-eval-0.4.2 1xml-5.2.2 markdown-it-py-3.0.0 markdown2-2.4.13 mbstrdecoder-1.1.3 mdur1-0.1.2 more-itertools-10.3.0 mpmath-1.3.0 multidict-6.0.5 multiprocess-0.70.16 n etworkx-3.3 neural_speed-1.0ae nh3-0.2.17 nltk-3.8.1 numexpr-2.10.1 numpy-1.23.5 nvidia-cublas-cu12-12.1.3.1 nvidia-cuda-cupti-cu12-12.1.105 nvidia-cuda-nvrtc-cu12-12.1.105 nvidia-cuda-r untime-cu12-12.1.105 nvidia-cudnn-cu12-8.9.2.26 nvidia-cufft-cu12-11.0.2.54 nvidia-curand-cu12-10.3.2.106 nvidia-cusolver-cu12-11.4.5.107 nvidia-cusparse-cu12-12.1.0.106 nvidia-nccl-cu12 -2.20.5 nvidia-nvjitlink-cu12-12.5.40 nvidia-nvtx-cu12-12.1.105 oneccl_bind_pt-2.3.0+cpu onnx-1.16.1 optimum-1.20.0 optimum-intel-1.17.2 orjson-3.10.5 pathvalidate-3.2.0 peft-0.6.2 porta locker-2.8.2 prompt-toolkit-3.0.47 protobuf-5.27.1 pyarrow-16.1.0 pyarrow-hotfix-0.6 pybind11-2.12.0 pydantic-1.10.13 pygments-2.18.0 pytablewriter-1.2.0 python-dotenv-1.0.1 python-multi part-0.0.9 rich-13.7.1 rouge_score-0.1.2 sacrebleu-2.4.2 sacremoses-0.1.1 sentencepiece-0.2.0 shellingham-1.5.4 shortuuid-1.0.13 sniffio-1.3.1 sqlitedict-2.1.0 starlette-0.37.2 svgwrite- 1.4.3 sympy-1.12.1 tabledata-1.3.3 tabulate-0.9.0 tcolorpy-0.1.6 tiktoken-0.4.0 torch-2.3.0 torchaudio-2.3.0 tqdm-multiprocess-0.0.11 transformers_stream_generator-0.0.5 triton-2.3.0 typ epy-1.3.2 typer-0.12.3 ujson-5.10.0 uvicorn-0.30.1 uvloop-0.19.0 watchfiles-0.22.0 wavedrom-2.0.3.post3 websockets-12.0 word2number-1.1 xxhash-3.4.1 yacs-0.1.8 yarl-1.9.4 zstandard-0.22.0


 # pip install -r requirements.txt



Requirement already satisfied: accelerate in /home/u9281ce8c87c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from -r requirements.txt (line 111 (0.28.0) Requirement already satisfied: cchardet in /home/u9281ce8c8e7c085602fa3241ebe2550/.conda/envs/itrex-1/11b/python3.10/site-packages (from requirements.txt (line 2)) (2.1.7) Requirement already satisfied: einops in /home/u9291ce8c8e7c085602fa721ebe2550/.conda/envs/trex-1/lib/python3.18/site-packages (from -r requirements.txt (line 3)) (8.8.8) Requirement already satisfied: evaluate in /home/u201ce8c87c885682fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (requirements.txt (line 4)) (8.4.27 Requirecent already satisfied: fastopi in /home/u201ce8e8e7c885682fa7241ebe2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from requirements.txt (line 5)) (0.111.0) Collecting fschat-0.2.35 (from requirements.txt (line 8))
using cached fochet-0.2.35-py3-none-any.wh1.metadata (19 kB
Requirement already satisfied: huggingface hub in /home/u9201ce8c8e7c885682fa7241eb2558/.conda/envs/trex-1/lib/python3. 16/site-packages (from -r requirements.txt (line 7)) (0.23.4) Requirement already satisfied; intel_extension_for_pytorche-2.3.0 in /home/u9281ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from requirements.txt (li ne 8)) [2.3.0+cpu) Requirement already satisfiedt Im-eval in /home/u9261ce8c8e7c885682fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from -r requirements.txt (line 9)) [2.4.2) Requirement already satisfied; neural-compressor in /home/p9281ce8ce7c065602fa7241ebe2550/.conda/envs/trex-1/lib/python3.18/site-packages (from requirements.txt (line 10)) (2.6) Requirement already satisfied: neural speed-1.ead in /home/u8201ce8ce7:085602fa7241cbe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from requirements.txt (line 11))-(1.000) Requirement already satisfied: numpy-1.23.5 in.bone/u201ce8c8e7c885662fa7241ebe2550.conda/envs/itrex-1/se/python3.16/site-packages (from requirements.txt (line 12)) (1.23.5) Requirement already satisfied: onnxs-1.15.0 in /home/u9201ce8c8e7c285682727241ebe2558/.conda/envs/1trex-1/1lb/python3.10/site-packages from requirements.txt (line 131 (1.16.1) Requirement already satisfied: optimum in /home/u201ce8c8e7c885682fa7241-be2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from - requirements.txt (line 1419 (3.20.8) Requirement already satisfied; optioun intet in /home/u201ce8c8e7c885662f7243ebo25582.conda/envs/itrex-1/lib/python3. 10/site-packages (from -r requirements.txt. (line 151) (1.17.2) Requirement already satisfied: peft-3.6.2 in /home/u201ce8c807c085602fa7241ebe2558/.conda/envs/itrex 1/lib/python3.18/site-packages (from requirements.txt (line 15)) 10.6.2) Requirement already satisfied: pymantic-1.10.13 In /home/u92@1ce8c8e7c885602fa7241ebe2558/.conda/envs/trex-1/lib/python3. 10/site-packages (from -r requirements.txt (line 17)) (1.10.13) Requirement already satisfied: python-doten. in /home/u9281ce8cbe7c085602fe7241be2550/.conda/enus/itrex-1/lib/python3.10/site-packages (from -r requirements.txt (line 18)) (1.0.1) Requirement already satisfied; pytboo-multipart jo /home/a8201ca8c8e2c0856827872412be2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from requirements.txt (line 193) (8:8-9) Requirement already satisfied: couge score in /home/u201ce8c8e7c085602fa7241ebe2958/.conda/envs/itrex-1/lib/python3.10/site-packages (from - requirements.txt (line 20)) (0.1.2) Requirement already satisfied: sacremoses in /home/u9201ce8c8e7c085602fa7241be2550/.conda/envs/1trex-1/11b/python3.18/site-packages (from requirements.txt (line 21)) (0.1.1) Requirement already satisfied: shartueld in /home/u9201ce8c87c8656e2fa7241-be2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from requirements.txt (line 22)) (1.8.13) Requirement already satisfied: starlette in /home/u9281ce8c8e7c085602fe7241be2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from -r requirements.txt (line 33) (0.37.2) 

Requirement already satisfied: pytablewriter in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from Im-eval->- requirements.txt (line 3)) (1.2. Requirement already satisfied: sacrebleu>=1.5.0 in /home/u9281ce8c8e7c8856824a7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from In-eval-- requirements.txt (line 9)) (2 42) Requirement already satisfied: scikit-learn-0,24.1 in /home/u201ce8c8e7c085682fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from leval->- requirements.txt (line.9) (1.5.0) Requirement already satisfied: siistiet in /home/d98cec8e705556272421598/.conda/envs/itrex-1/lib/python3.10/site-packages (from be-eval-requirements.ese (line 831 (2.146) Requirement already satisfied: catalpoms in /home22@cec87c085602f6724cbe255/tandarenstrex-2/2b/pythond. 10/site-packages (from letaloquirements.txt flion 9) ( 0.0.11) Requirement already satisfied: ostendard in /home/u9201ce8c8e7c885682fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from in-eval->-r requirements txt (ie 911 (8.12.0 Requirement already satisfied: aordinumber 1m7602672416252.conda/envs/brew-1/lib/pythonste-packages/n-val- requirements.txt (line 8) (1.1) Requirement already satisfied: hormitoctonis in /home/u9281ce6c8e7c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from im-valorequirements txt (line 1 tio. 3601 Requirement already satisfied: deprecated 1.2.13 in /home/u9291ce6c87c085601fa7241be2558/.conda/envs/tres-1/lib/python3.18/site-packages (from neural-compressor->requirements.txt (line 10) (1.2.14) Requirement already satisfied: opency python-headless in /home/u9261ce8ce7c085602fa7241che2590/.conda/envs/itrex-1/lib/python3.16/site-packages (from neural-compressorer requirements. txt (line 1834.10.0.84) Requirement already satisfied: Pillow in home/u9281cebca=7c855602fa7241be2556/.conda/envs/itrex-1/lib/python3.18/site-packages (from neural-compressor-x requirements.txt (1= 19)) ( 18:3:8) Requirement already satisfied: prettytable in /home/u9201ce8c8e7c885602fa7241cbe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from neural-compresson-y requirements.txt (line 1 8)) (3.10.0) Requirement already satisfied: py-cpuinfo in /home/u901ce8c3e76055602fe7141be2550/.conda/en/s/1trex-1/116/python3.10/site-packages (from hers! compressor requirements.txt (1:18 33 (0.0.0 Requirement already satisfied: schons in /home/u9291cec5e7c035602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.1/site-packages (from neural popressorer requirements.txt (line 28)) ( Requirement already satisfled: pycocotools in /home/u9201ce8c8e7c885692fa7241ebe2558/.conda/envs/1trex-1/lib/python3.10/site-packages (from neural-compressor-2-r requirements txt line 1 01) (2.8.8) Requirement already satisfied: protobuf-3.28.2 in /home/u9201ce8c8e7c885682a7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from onmo-1.15.6-- requirements.txt (line 1 3)) (5:27) Requirement already satisfied: coloredlegs in /home/u201ce8c87c0556ea7241ebe2550/.conda/envs/itrex-1/lib/python3.19/site-packages (from optimum requirements.txt (lins 14)) (15.6. Requirement already satisfied: sentencepiece in /home/u920ice8c8e7c089602+07241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from optimum intel- requirements.txt (line 15) ) (0.2.0) Requirement already satisfied: cetuptools In /home/u9281ce8c8e7c085602fa7241be2558/.conda/envs/1trex-1/lib/python3.18/site-packages (from optimum-Intel-x-requirements.txt (line 15)) ( 69.5.1) Requirement already satisfied; scipy in /home/u201ce8c8e7c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from optimum intel-- requirements.txt (line 15)) (1.13. Requirement already satisfied: absl-py in /home/u9201ce8c8e7c885602fa7241be2550/.conda/envs/itrex-1/lib/python3.16/site-packages (from rouge score->- requirements.txt (line 20)) (2.1.8 Requirement already satisfied: nitk in /home/u9201ce8c8e7ce85602fa7241ebe2550/.conda/envs/iteex-1/lib/python3.18/site-packages (from rouge score-x-r requirements.txt (line 20)) (3.8.1). Requirement already satisfied: six-1.14.0 in /home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from rouge score-r requirements.txt (line 20)) (1) .16.0). Requirement already satisfied: regex in /home/u9201ce8c8e7c885682f87241ebe2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from sacremoses-- requirements.txt (line 21)) (2024.5.1 Requirement already satisfied: click in /home/u9291ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from sacremoses-> requirements.tict (line 21)) (8.1.7) Requirement already satisfied: Joblib in /home/u9201ce8c8e7c085602fa7241be2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from sacremoses-x-r requirements.txt (line 21)) (1.4.2) Requirement already satisfied: anyia 5, -3.4.3 in /home/u201ce6c8e7c5682fa7241be2558/.conda/envs/itrex-1/lib/python3-16/site-packages (from staristte-requirements.txt (line 23) 14:4.8) Collecting astunparse -1.6.0 from tensorflow-2.13.0-
1)
.
53
requirements.txt (line 24))
Using cached astumparse-1.8.3-py2.py3-none/ahy-metadata 14.4 KB)
Collecting Flatbuffas 23.5.26 (from sensorf Lou-2.13.0-require txt (line 24)). Using cached Flatbyfters 24.25-py.py3-none-any-whi.metadata (as bytas)


Collecting grpclox2.0,>=1.24.3 (from tensorflows-2.13.8-- requirements.txt (line 24))
Using cached grpcio-1.64.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.hl.metadata (3.3 kB) Collecting tensorboard<2.17,-2.16 (from tensorflow-2.13.0-r requirements.txt (line 24))
Using cached tensorboard-2.16.2-py3-none-any.wh1.metadata (1.6 kB)
Collecting keras >-3.0.0 (from tensorflow>=2.13.0-x-r requirements.txt (line 24))
Using cached keras-3.3.3-py3-none-any.whl.metadata (5.7 kB)
Collecting tensorflow-io-ges-filesystem-0.23.1 (from tensorflow 2.13.0->-r requirements.txt (line 24))
Using cached tensorflow_io_gcs_filesystem-0.37.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1.metadata (14 kB)
Requirement already satisfied: tokenizers<0.20, 0.19 in /home/u9201ce8c8e7c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from transformers-4.35.2->- requiremen ts.txt (line 27)) (0.18.1)
Requirement already satisfied: h11-0.8 in /home/u9281ce8c8e7c085682787241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from uvicorn->-r requirements.txt (line 29)) (0.14.0) Collecting cmake-3.21 (from vllm->-r requirements.txt (line 38)) Dowmloading cmake-3.29.6-py3-none-manylinux_2_17_x86_64.many linux2014_x86_64.h1.metadata (6.1 kB)
Collecting ninja (from vlls->- requirements.txt (line 301)
Using cached ninja-1.11.1.1-py2.py3-none-many linux_x86_64 manylinux_2_5_x86_64.h1.metadata (5.3 k6)
Collecting openai (from vlln--n requirements.txt (line 30))
Downloading opena1-1.35.3-py3-none-any.whi.metadata (21 kB)
INFO: pip is looking at multiple versions of vilm to determine which version is compatible with other requirements. This could take a while. Collecting vilm (from requirements.txt (line 30))
Using cached vilm-0.5.0-cp310-cp310-manylinux-x86_64, uhl metadata (8.3 kB) Using cached vilm-0.4.3-cp310-cp310-manylinux1_x86_64.h1.metadata (7.8 kB) Using cached vilm-0.4.2-cp310-cp310-menylinux x86.64.whk.metadata (9.1 kB) Using cached vll-0.4.1-cp310-cp310-manylinux1_x86_64, wh1.metadata (8.9 kB)
Using cached v11m-0.4.0.posti-cp310-cp310-manylinux1_x86_64.wh1.netadata (8.6 kB) Collecting tay>-2.9 (from vllm--r requirements.txt (line 30))
Downloading ray-2.30.0-cp318-ep310-manylinux2014-x86_64.hl.metadata (13 kB) Collecting vilm (from requirements.txt (line 30))
Using cached 11-0.4.0-cp310-cp210-manylinux1_x86_64.h1.metadata (8.6 kB] Using cached vilm-0.3.3-cp310-cp310-manylinux1_x86_64.unl.metadata (7.8 kB]
INFO: pip is still looking at multiple versions of vlls to determine which version is compatible with other requirements. This could take a while.
Using cached vile-0.3.2-cp310-cp310 many linux x86_64.hl.metadata (7.5 kB) Using cached 911m-0.3.1-cp310-cp310-manylinux1_x86_64.wh1.metadata (7.4 kB) Using cached vll-0.3.0-cp310-cp310-manylinux x86_64.unl.metadata (7.4 kB) Using cached vlim-0.2.7-cp310-cp210-manylinux1_x86_64.hl.metadata (6.8 kB) Using cached vlim-0.2.6-cp310-cp310-many linux1_x86_64.h1.metadata (6.7 kB)
Requirement already satisfied: pyarrow in /home/u9261ce8c8e7c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from vllm-- requirements.txt (line 30)) (16.1.0) INFO: This is taking longer than usual. You might need to provide the dependency resolver with stricter constraints to reduce runtime. See https://pip.pypa.io/warnings/backtracking for g uidance. If you want to abort this run, press Ctrl + C. Using cached vllm-0.2.5-cp310-ce310-manylimux1_x86_64.h1.metadata (6.5 KB)
Collecting xformers-0.0.23 (from: vllm-> requirements.txt (line 30))
Using cached xformers-0.0.26.posti-cp318-cp310-manylinux2014_x86_64.wh1.metadata (1.8 KB) Collecting aidprometheus [starlette] (from vlim->-r requirements.txt (line 30))
Using cached aioprometheus 23.12.0-py3-none-any.wh1.metadata (9.8 kB)
Requirement already satisfied: idna-2.8 in /home/u9201ce8c8e7c0856e2fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from anyio<5>3.4.0->starlette-- requirements.txt (line 23)) (3.7) Requirement already satisfied: sniffiox 1.1 in /home/u9201ce8c8e7c885682fe7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from anyio<5, 3.4.0-starlette->-r requirements.t xt (line 23)) (1.3.1). Requirement already satisfied: exceptiongroups-1.0.2 in /home/u9201ce8c8e7ce85602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from anyio<5,>-3.4.0->starlette->- requi rements.txt (line 23)) (1.2.1)
Requirement already satisfied: wheel 1.0, -0.23.0 in /home/u9201ce8c8e7c885602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from astunpersex-1.6.0-tensorflow>=2.13.8- r requirements.txt (line 241) (0.43:0)


requirements.txt (line 4
Requirement already satisfied: humanfriendly-91 in /home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from coloredlogs-soptimum requirements.t xt (line 14)) (10.0) Requirement already satisfied: wavedrom in /home/u9201ce8c87c885682724lebe2550.conda/envs/itrex-1/lib/python3.10/site-packages (from markdown?[all]->fschar=-0.2.35--r requirements.c xt (line 6)) (2.0.3.post3) Requirement already satisfied: python-dateutils-2.8.2 in /home/u9281ce8c8e7c085602fa241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from pandas-evaluate requirements.t xt (line 4)) (2.9.0.poste) Requirement already satisfied: pytz>=2020.1 in /home/u9201ce8c8=7c0656827241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from pandas-evaluate }) (2024.1) Requirement already satisfied: tzdata-2022.7 in /home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from pandas->evaluates requirements txt (line 4)) (2024.1) Requirement already satisfied: matplotlib>-2.1.8 in /home/u9281ce8c8e7c08560287241ebe2556/.conda/envs/itrex-1/lib/python3.10/site-packages (from pycocotools->neural-compressor->- requi rements.txt (line 10)) (3.9.0) Requirement already satisfied: DataProperty<2,>-1.0.1 in /home/u9201ce8c8e7c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from pytablewriter->1m-eval-> ents.txt (line 9) (1.0.1)
requirem
Requirement already satisfied: abstrdecoder<2>=1.0.0 in /home/u9281ce8c8e7c885682fe7241be2558/.conda/envs/itrex-1/lib/python3.10/site-packages (from pytableuriter-la-evel->-r requirem ents.txt (line 9)) (1.1.3) Requirement already satisfied: pathvalidate 4, -2.3.0 in /home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from pytablewriter-im-eval->- requirem ents.txt (line 9)) (3.2.0)
Requirement already satisfied: tabledata<2,1.3.1 in /home/u9281ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from pytablewriter->im-eval--r requirement s.txt (line 9)) (1.3.3)
Requirement already satisfied: tcolorby (1,>-0.0.8 in /home/u9281ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from pytablewriter->Imieval .txt (line 91) (0.1.6)
requirements
Requirement already satisfied: typepy 2,1.3.2 in /home/u9201ce8c8e7c885682fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from typepy datetime] <2,>=1.3.2->pytableuriter lm-eval-- requirements, txt (line 3)) (1.8.21
Requirement already satisfied: path 1.4.0.5-1.1.0 in /home/u201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from syepy-torch-2.3.0-- requirements. txt (line 25)) (1.3.0) Requirement already satisfied; nidurive8.1 in /home/u201ce8ce7c0856027241be2550/.conda/envs/lerex-1/lib/python3.16/site-packages (from markdown-t-py2.2.0-rich-18.0.0->fschat:=2. 2.35- requirements.txt (line 6)) (0.1-2) Requirement already satisfied: contourpy-1.0.1 in /home/u9291ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib-2.1.0-py cocotools-neural-co mpressor-- requirements.txt (line 18)) (1.2.1) Requirement already satisfied: cyclers=0.10 in /home/u201ce8c87c085682a7241be2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib-2.1.8-spycocotools-neural-compre ssor-er requirements.txt (line 10)) (0.12.1) Requirement already satisfied: fonttools-4.22.0 in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from watplotlib-2.1.0-pycocotools-neural-c ompressor--r requirements.txt (line 18)) (4.53.0) Requirement already satisfied: kiwisolver-1.3.1 in /home/u9201ce8c8e7c085602f87241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib>=2.1.0-pycocotools-neural-c ompressor - requirements.txt (line 10)) (1.4.5) Requirement already satisfied: pyparsings-2.3.1 in /home/u9201ce8c8e7ce85602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from matplotlib-2.1.0-pycocotools+ neural-co mpressor->- requirements.txt (line 10)) (3.1.2) Requirement already satisfied: chardetco,>=3.0.4 in /home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from abstrdecoder<2>=1.0.0-pytablewriter->1 m-eval- requirements.txt (line 9)) (5.2.0)


Collecting jsonschema-specifications>=2023.03.6 (from jsonschema-ray>=2.9->llm->-r requirements.txt (line 30)) Using cached sonschema_specifications-2023.12.1-py3-none-any.whl.metadata (3.0 kB)
Collecting referencing>-0.28.4 (from jsonschema-ray-2.9->vllm-r requirements.txt (line 30))
Using cached referencing-0.35.1-py3-none-any.wh1. metadata (2.8 kB)
Collecting rpds-pyx-0.7.1 (from Jsonschema->ray>=2.9-xvllm->-r requirements.txt (line 38))
Using cached rpds_py-0.18.1-cp310-cp310-manylinux_2_17_x86_64.many linux2014_x86_64.whl.metadata (4.1 kB)
Requirement already satisfied: sygwrite in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from wavedrom->markdown2 [all]->fschat--8,2.35->-r requ irements.txt (line 6)) (1.4.3)
Using cached fschat-0.2.35-py3-none-any.wh1 (226 kB)
Using cached tensorflow-2.16.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2814_x86_64.whl (589.8 MB)
Using cached vllm-0.2.5-cp310-cp318-manylinux1_x86_64.whl (9.8 MB)
Using cached astumparse-1.6.3-py2.py3-none-any.whl (12 kB)
Using cached flatbuffers-24.3.25-py2.py3-none-any.wh1 (26 kB)
Using cached gast-8.6.4-py3-none-any.whl (19 kB)
Using cached google_pasta-0.2.0-py3-none-any.whl (57 kB)
(5.3 MB)
Using cached grpcio-1.64.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.wh1 (5.66) Using cached h5py-3.11.0-cp310-cp310-many linux_2_17_x86_64.manylinux2014_x86_64.h1 Using cached keras-3.3.3-py3-none-any.whl (1.1 MB)
Using cached libclang-18.1.1-py2.py3-none-manylinux2010_x86_64. wh1 (24.5 MB)
Using cached ml dtypes-0.3.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64,wh1 (2.2 MB) Using cached opt_elnsum-3.3.0-py3-none-any.wh1 (65 kB)
Using cached protobuf-4.25.3-cp37-abi3-manylinux2014 x86_64.whl (294 kB) Downloading ray-2.30.0-cp310-cp310-manylinux2014_x86_64.whl (66.0 MB)
60/66 34.6 MB/s eta 8:00:00
Using cached tensorboard-2.16.2-py3-none-any.whl (5.5 MB)
Using cached tensorflow_io_gcs_filesystem-8.37.0-cp310-cp318-menylinux_2_17_x86_64.manylinux2014_x86_64.whl (5.1 MB)
Using cached termcolor-2.4.0-py3-none-any.whl (7.7 kB)
Using cached xformers-0.0.26.post1-cp310-cp310-manylinux2014_x86_64.h1 (222.7 MB)
Using cached ninja-1.11.1.1-py2.py3-none-many linux1_x86_64.manylinux_2_5_x86_64.hl (387 kB)
Using cached Markdown-3.6-py3-none-any.whl (105 k6)
Using cached msgpack-1.0.8-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.h1 (385 kB)
Using cached tensorboard_data_server-0.7.2-py3-none-manylinux_2_31_x86_64.wh1 (6.6 MB)
Using cached werkzeug-3.0.3-py3-none-any.whl (227 kB)
Using cached aioprometheus-23.12.0-py3-none-any.whl (31 kB)
Using cached json schema-4.22.0-py3-none-any.whl (88 kB)
Using cached namex-0.0.8-py3-none-any.wh1 (5.8 kB)
Using cached optree-0.11.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.h1 (311 kB)
Using cached jsonscheme specifications-2023.12.1-py3-none-any.whl (18 kB)
Using cached referencing-0.35.1-py3-none-any.whl (26 kB)
Using cached rpds_py-0.18.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.h1 (1.1 MB)
Installing collected packages: quantile-python, ninja, namex, libclang, flatbuffers, werkzeug, termcolor, tensorflow-lo-gcs-filesystem, tensorboard-data-server, rpds-py, protobuf, optree , opt-einsum, msgpack, ml-dtypes, markdown, h5py, grpcio, google-pasta, gast, astunparse, aloprometheus, tensorboard, referencing, keras, jsonschema-specifications, xformers, tensorflow, jsonschema, ray, vllm, fschat
Json schema, ray, vllm, fschat. Attempting uninstall: protobuf
Found existing installation: protobuf 5.27.1 Uninstalling protobuf-5.27.1:
Successfully uninstalled protobuf-5.27.1 
Attempting uninstall: fschat
Found existing installation: fschat 0.2.32
Uninstalling fschat-0.2.32:
Successfully uninstalled fschat-0.2.32
Successfully installed aioprometheus-23.12.0 astumparse-1.6.3 flatbuffers-24.3.25 fschat-0.2.35 gast-0.5.4 google-pasta-0.2.0 grpcio-1.64.1 h5py-3.11.0 jsonschema-4.22.0 jsonschema-speci fications-2023.12.1 keras-3.3.3 11bclang-18.1.1 markdown-3.6 ml-dtypes-0.3.2 msgpack-1.0.8 namex-0.0.8 ninja-1.11.1.1 opt-einsum-3.3.0 optree-0.11.0 protobuf-4.25.3 quantile-python-1.1 r ay-2.30.0 referencing-0.35.1 rpds-py-0.18.1 tensorboard-2.16.2 tensorboard-data-server-0.7.2 tensorflow-2.16.1 tensorflow-io-gcs-filesystem-0.37.0 termcolor-2.4.0 vilm-0.2.5 werkzeug-3.0 .3 xformers-0.0.26.post1

# huggingface-cli login

HUGGING FACE
A token is already saved on your machine. Run huggingface-cli whoami to get more information or huggingface-cli logout if you want to log out. Setting a new token will erase the existing one.
To login, huggingface_hub requires a token generated from https://huggingface.co/settings/tokens.
Enter your token (input will not be visible): “XXXX XXXX”

# python3 -m pip install jupyter ipykernel



Collecting tomli>-1.2.2 (from jupyterlab 4.3, 4.2.0-notebook->jupyter)
Using cached tom14-2.0.1-py3-none-any.wh1.metadata (8.9 kB)
Collecting babel>=2.10 (from jupyterleb-server<3,>=2.27.1-notebook->jupyter) Using cached Babel-2.15.0-py3-none-any.whl.metadata (1.5 kB)
Collecting json5-8.9.8 (from jupyter lab-server<3,>=2.27.1-notebook->jupyter) Using cached son5-0.9.25-py3-none-any.wh1.metadata (30 kB)
Requirement already satisfied: jsonschens>-4.18.0 in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/14b/python3.18/site-packages (from jupyterlab-server<,>=2.27.1->notebook- jupyter) (4.22.0)
Requirement already satisfied: requests-2.31 in /home/u9281ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from jupyterlab-server<3, -2.27.1-notebook->jup yter) (2.32.3)
Collecting fast sanschema-2.15 (from abforest>5.7-nbconvert-jupyter)
Using cached fastjsonschema 2.20.0-py3-none-any.whi.metadata (2.2 kB) Collecting ptyprocess-8.5 (from pexpect 4.3->ipython-7.23.1->ipykernel) Using cached ptyprocess-8.7.0-py2.py3-none-any.wh1.metadata (5.3 kB)
Requiresens already satisfied: wcwidth in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from prompt-toolkit 3.1.0,>=3.8.41->python-7.23.1->ip ykernel) (0.2.13) Collecting soupsieve>1.2 (from beautifulsoup4-nbconvert-jupyter) Using cached soopsieve-2.5-py3-none-any.wh1.metadata (4.7 kB) Collecting executing>=1.2.0 (from stack-date->ipython-7.23.1->ipykernel) Using cached executing-2.0.1-py2.py3-none-any.whl.metadata (9.0 kB) Collecting asttokens-2.1. (from stack-data-ipython-7.23.1-ipykernel) Using cached asttokens-2.4.1-py2.py3-none-any.whl.metadata (5.2 kB)) Collecting pure-evel (from stack-data->python-7.23.1-bipykernel) Using cached pore_eval-0.2.2-py3-none-any.wh1.metadata (5.2 kB] Requirement already satisfied: idna-2.8 in /home/u201ce8c8e7c885502fa7241ebe2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from anyio>-3.1.0-jupyter server 3,-2.4.0->notebook Jupyter) (3.7)
Requirement already satisfied: sniffi>=1.1 in /home/u9281ce8ca7c085602fe7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from anyiox=3.1.0->jupyter-server<3,>=2.4.8-noteb oak-jupyter) (1.3.1) Collecting argon2-cffi-bindings (from argon2-cffi-21.1-jupyter-server<3>-2.4.0-notebook->jupyter)
Using cached argon2_cffi_bindings-21.2.0-cp36-ab13-manylinux_2_17_x86_64.manylinux2014_x86_64.hl.metadata (6.7 kB)
Requirement already satisfied: centiti in /home/u201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from httpx-0.25.e-jupyterlab<4.3,-4.2.0-notebook-> upyter) (2024:6,2),... Requirement already satisfied: httpcore-1." in /home/u9201ce8c8e7ce85602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from httpx>-8.25.8-jupyterlab 4.3, -4.2.8-noteb ock-jupyter) (1.8.5) Requirement already satisfied: hi10.15, 0.13 in /home/u201ce8c8e7c885682fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from httpcore=1.->httpx>=0.25.0->jupyter lab 4 .3.4.2.0-notebook->jupyter) (0.14.0) Requirement already satisfied: attrs 22.2.0 in /home/u9281ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from jsonschemas-4,18,0->jupyterlab-server<3,>=2. 27.1-notebook-Jupyter) (23.2.0) Requirement already satisfied: jsanschema-specifications>-2023.03.6 in /home/u9201ce8c87c8856827241ebe2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from jsonschems>=4.18.6-xj upyterlab-server<3, 2.27.1-notebook->jupyter) (2023.12.1) Requirement already satisfied: referencing -0.28.6 in /home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from jsonschema-4.18.8.jupyterlab-server< 3,>=2.27.1-notebook->jupyter) (0.35.1) Requirement already satisfied: rpds-py2.7.1 in /home/u9281ce8c8e7c065602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.18/site-packages (from jaanschens-4.18.0-jupyterlab-server<3,>=2 27-1-notebook-jupyter) (0.18.1) Collecting python-json-loggers-2.8.4 (from jupyter-events-0.9.0->jupyter server 3,-2.4.0-notebook->jupyter)
Using cached python_json_logger-2.0.7-py3-none-any.wh1.metadata (6.5 KB)
Requirement already satisfied: pyyaml-5.3 in /home/u9201ce8c8e7c885602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from jupyter-events-0.9.0->jupyter-server<3,>=2.4. ->notebook->jupyter) (6.0.1) Collecting rfc3339-validator (from jupyter-events-0.8.0->jupyter serven 3, -2.4.0-notebook->Jupyter)
Using cached rfc3339_validator-8.1.4-py2.py3-none-any.wh1.metadata (1.5 kB)
Collecting rf3986-validator>-8.1.1 (from jupyter-events-0.9.8->jupyter-server<3,>=2.4.8-notebook->jupyter) Using cached efc3996_validator-0.1.1-py2.py3-none-any.wh.metadata (1.7 kB)


Using cached jupyterlab-4.2.2-py3-none-any.whl (11.6 MB) Using cached jupyterlab_server-2.27.2-py3-none-any.whl (59 kB) Using cached jupyterlab_widgets-3.0.11-py3-none-any.whl (214 kB) Using cached mistune-3.0.2-py3-none-any.whl (47 kB)
Using cached nbclient-0.10.0-py3-none-any.wh1 (25 kB)
Using cached nbformat-5.10.4-py3-none-any.whl (78 kB)
Using cached notebook_shim-0.2.4-py3-none-any.whl (13 kB) Using cached pandocfilters-1.5.1-py2.py3-none-any.whl (8.7 ke) Using cached pexpect-4.9.0-py2.py3-none-any.wh1 (63 kB) Using cached platformdirs-4.2.2-py3-none-any.whl (18 kB) Using cached QtPy-2.4.1-py3-none-any.whl (93 kB)
Using cached widgetsnbextension-4.0.11-py3-none-any.whl (2.3 MB) Using cached beautifulsoup4-4.12.3-py3-none-any.whl (147 kB) Using cached decorator-5.1.1-py3-none-any.wh1 (9.1 kB) Using cached defusedxml-0.7.1-py2.py3-none-any.whl (25 kB) Using cached jupyterlab_pygments-0.3.0-py3-none-any.whl (15 kB) Using cached stack_data-0.6.3-py3-none-any.whl (24 kB) Using cached tinycss2-1.3.0-py3-none-any.whl (22 KB) Using cached argon2_cffi-23.1.0-py3-none-any.whl (15 kB) Using cached asttokens-2.4.1-py2.py3-none-any.whl (27 kB) Using cached async_1ru-2.0.4-py3-none-any.wh1 (6.1 kB) Using cached Babel-2.15.0-py3-none-any.whl (9.6 MB) Using cached executing-2.0.1-py2.py3-none-any.whl (24 kB) Using cached fastjsonschema-2.20.0-py3-none-any.whl (23 kB) Using cached son5-0.9.25-py3-none-any.wh1 (30 kB)
Using cached jupyter_events-0.10.0-py3-none-any.whl (18 kB)
Using cached jupyter 1sp-2.2.5-py3-none-any.whl (69 kB)
Using cached jupyter_server_terminals-0.5.3-py3-none-any, wh1 (13 kB) Using cached overrides-7.7.0-py3-none-any.whl (17 kB)
Using cached parso-0.8.4-py2.py3-none-any.whl (103 kB)
Using cached prometheus client-0.20.0-py3-none-any.whl (54 kB)
Using cached ptyprocess-0.7.0-py2.py3-none-any.wh1 (13 kB)
Using cached Send2Trash-1.8.3-py3-none-any.whl (18 kB)
Using cached soupsleve-2.5-py3-none-any.whl (36 kB) Using cached terminado-0.18.1-py3-none-any.whl (14 kB) Using cached tomli-2.0.1-py3-none-any.wh1 (12 kB)
Using cached webencodings-0.5.1-py2.py3-none-any.wh1 (11 kB) Using cached websocket_client-1.8.0-py3-none-any.whl (58 kB)
Using cached pure_eval-0.2.2-py3-none-any.whl (11 kB)
Using cached python_json_logger-2.8.7-py3-none-any.whl (8.1 kB)
Using cached rfc3986_validator-0.1.1-py2.py3-none-any.wh1 (4.2 kB)
Using cached argon2_cffi_bindings-21.2.0-cp36-ab13-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (86 kB) Using cached rfc3339_validator-0.1.4-py2.py3-none-any.whl (3.5 kB)


A token is already saved on your machine. Run huggingface-cli whoami to get more information or huggingface-cli logout if you want to log out. Setting a new token will erase the existing one. To login, hugging face hub requires a token generated from https://huggingface.co/settings/tokens. Enter your token (input will not be visible): Traceback (most recent call last):
File "/home/u9201ce8c8e7ce85602fa7241ebe2550/.conda/envs/itrex-1/bin/huggingface-cli", line 8, in <module>
sys.exit(main())
File
"/home/u9281ce8c8e7c085602f87241ebe2558/.conda/envs/itrex-1/lib/python3.10/site-packages/huggingface_hub/commands/huggingface_cli.py",
service.run()
File "/home/u9201ce8c8e7c085602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages/huggingface_hub/commands/user.py",
login(token=self.args.token, add to_git_credential-self.args.add_to_git_credential)
line 51, in main
line 98, in run
File "/home/u9201ce8c8e7c085602fb7241ebe2550/.conda/envs/itrex-1/lib/python3.18/site-packages/huggingface_hub/_login.py", line 115, in login interpreter_login(new_session-new_session, write_permission-write_permission)
File "/home/u9201ce8c8e7c085682fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages/huggingface_hub/_login.py", line 191, in interpreter login token getpass("Enter your token (Input will not be visible): ")
File "/home/u9201ce8c8e7c085602fa7241ebe2558/.conda/envs/itrex-1/lib/python3.18/getpass.py", line 77, in unix_getpass passed - _raw_input(prompt, stream, input-input)
File "/home/u9201ce8c8e7ce85682fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/getpass.py", line 146, in _raw_input line input.readline()
KeyboardInterrupt
(itrex-1) u9201ce8c8e7c085602fa7241ebe2550@ido-training-gpu-compute-13:~/intel-extension-for-transformers/intel_extension_for_transformers/neural_chats python3 -m pip install jupyter ipy kernel
Collecting jupyter
Using cached jupyter-1.0.0-py2.py3-none-any.whi.metadata (995 bytes)
Collecting ipykernel
Using cached Ipykernel-6.29.4-py3-none-any.whl.metadata (6.3 KB)
Collecting notebook (from jupyter)
Using cached notebook-7.2.1-py3-none-any.wh1.metadata (10 kB)
Collecting qtconsole (from jupyter)
Using cached qtconsole-5.5.2-py3-none-any.wh1.metadata (5.1 kB)
Collecting jupyter-console (from jupyter)
Using cached jupyter_console-6.6.3-py3-none-any.wh1.metadata (5.8 k6)
Collecting nbconvert (from jupyter)
Using cached nbconvert-7.16.4-py3-none-any.wh1.metadata (8.5 kB)
Collecting ipywidgets (fran jupyter)
Using cached ipywidgets-8.1.3-py3-none-any.whl.metadata (2.4 kB)
Collecting com-0.1.1 (from ipykernel)
Using cached comm-0.2.2-py3-none-any.wh1.metadata (3.7 kB)
Collecting debugpy-1.6.5 (from ipykernel)
Using cached debugpy-1.8.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.h1.metadata (1.1 kB)
Collecting ipython>-7.23.1 (from ipykernel).
Using cached ipython-8.25.0-py3-none-any.wh1.metadata (4.9 kB)
Collecting jupyter-client -6.1.12 (from ipykernel)
Using cached jupyter_client-8.6.2-py3-none-any.whl.metadata (8.3 kB)
Collecting jupyter-core-5.0., 4.12 (from 1pykernel)
Using cached jupyter core-5.7.2-py3-none-any.whl.metadata (3.4 KB)
Collecting matplotlib-inline>-0.1 (from ipykernel)
Using cached matplotlib_inline-0.1.7-py3-none-any.whl.metadata (3.9 kB)
Collecting nest-asyncio (From ipykernel)
Using cached nest_asyncio-1.6.0-py3-none-any.whl.metadata (2.8 KB)
Requirement already satisfied: packaging in /home/u9281ce8c8e7c085602fa7241be2550/.conda/envs/itrex-1/lib/python3.18/site-packages (from ipykernel) (24.1) Requirement already satisfied: psutil in /home/u9201ce8c8e7c065602fa7241ebe2550/.conda/envs/itrex-1/lib/python3.10/site-packages (from ipykernel) (6.0.0)

# python3 -m ipykernel install --name neural-chat-1 –user

Installed kernelspec neural-chat-1 in /Users/your_username/Library/Jupyter/kernels/neural-chat-1








