# DESY_ML_PyTorch


These are tutorials held at DESY for HEP (and Astroparticle) physicists

To get the tutorials:

`git clone https://github.com/dkgithub/DESY_ML_PyTorch.git`

Connect to your machine with a tunnel:

`mkdir tmp`

`ssh -i A_DESY.pem -S./tmp  -L 1080:127.0.0.1:8888 user@machine`

To get the right environment

* on AWS (Amazon)

`cd DESY_ML_PyTorch`

`source startROOT.sh`

`jupyter lab --no-browser`

Look for the token.

Access the jupyter server on your laptop: http://localhost:1080/
Copy the token as password.

If you are working on a machine with different people jupyter will look for a free port number.
If this happens you need to connect by the above (1080:127.0.0.1:8888<--change to something free, e.g. 1234)

`jupyter lab --no-browser --port 1234`

Navigate to the files

Pick the "conda_pytorch_p27" environment for all except the create toy example below.

______________________________________________

The createToy.ipynb example needs a different setup!! Pick the _python2_ environment!!
