## Basic demonstration of Fast Fourier Transform (FFT) algorithm
Performs basic **signal processing** on audio, such as FFT algorithm and filter construction.

Follow the demo/instructions in the **interactive python notebook (.ipynb)** file located in the repository.
The **.wav** file is the audio waveform that will be modified. The **.yml** file includes dependencies required to run the python script. 

If you do not already have **conda** installed, you can **pip install** the dependencies but it is not recommended. 

If you do have conda, create a conda environment with the given .yml file and activate it. Once it is activated, open up the .ipynb file.

**Setup Instructions:**

Navigate using **command line** into folder containing repository, then run the following commands:

* *conda env create -f FourierDependency.yml*
* *conda activate FourierDependency*
* *jupyter lab*

Mathematical reference: https://en.wikipedia.org/wiki/Fourier_Transform
