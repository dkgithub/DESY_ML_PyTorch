# DESY_ML_PyTorch


These are tutorials held at DESY for HEP (and Astroparticle) physicists

To get the tutorials:

`git clone https://github.com/dkgithub/DESY_ML_PyTorch.git`

Connect to your machine with a tunnel:

`mkdir tmp`

`ssh -i A_DESY.pem -S./tmp  -L 1080:127.0.0.1:8888 user@machine`

To get the right environment
* on AWS (Amazon)

`source /home/ubuntu/anaconda3/etc/profile.d/conda.sh`

`conda activate pytorch_p27`

`source /home/ubuntu/root/bin/thisroot.sh`

Start the jupyter notebook

`jupyter lab --no-browser`

Look for the token.

Access the jupyter server on your laptop: http://localhost:1080/
Copy the token as password.

If you are working on a machine with different people jupyter will look for a free port number.
If this happens you need to connect by the above (1080:127.0.0.1:8888<--change to something free, e.g. 1234)

`jupyter lab --no-browser --port 1234`

______________________________________________

The createToy.ipynb example needs a different setup!!!

`source startROOT.sh`

and pick the python2 environment!!
