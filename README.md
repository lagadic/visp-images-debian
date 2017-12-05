# visp-images

visp-images contains data useful to run [ViSP][1] examples.

## Getting visp-images

- To get visp-images dataset as a zip archive corresponding to a release just [visit download page][2].

- To get the dataset using git:

		$ git clone https://github.com/lagadic/ViSP-images.git
		
## Setting ViSP-images

To use the data set you have to set `VISP_INPUT_IMAGE_PATH` environment variable:

- on unix-like platforms:

		$ export VISP_INPUT_IMAGE_PATH=<path to visp-images directory>

- on windows platforms:

		$ setx VISP_INPUT_IMAGE_PATH <path to visp-images directory>

## Example

The following example that can be achieved on unix-like platforms allows to use the data set installed in `/home/user/visp-ws/visp-images`:

	$ cd $HOME/visp-ws
	$ git clone https://github.com/lagadic/visp-images.git
	$ export VISP_INPUT_IMAGE_PATH=/home/user/visp-ws/visp-images


[1]: http://visp.inria.fr "ViSP"
[2]: http://visp.inria.fr/download "ViSP download"
