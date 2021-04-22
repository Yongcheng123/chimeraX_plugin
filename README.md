# ChimeraX_Plugin

This is a deeplearning based bundle for ChimeraX (for macOS).

# Requirements

  * ChimeraX

> Download [ChimeraX](https://www.cgl.ucsf.edu/chimerax/download.html). 

  * Dependencies (The dependencies don't need to be installed manually, you may update dependencies versions through bundle_info.xml)
>   ChimeraX-Core version="~=1.0"

>   [Torch >=1.4.0](https://pytorch.org/)

>   [numpy >=1.16.4](https://pypi.org/project/numpy/)

>   [importlib-metadata >=0.17](https://pypi.org/project/importlib-metadata/#history)

# Download and Install the bundle (for macOS)

  * [Download the test_plugin bundle](https://github.com/Yongcheng123/test_plugin)

>  I recommend you download this file to you Desktop directory, so that you don't have to modify any path.

  * Install the bundle into ChimeraX (Change USER_NAME to a specific one)

> 1. Run ChimeraX, you will see the Command box on the bottom

> 2. Build bundle by using command: devel build /Users/USER_NAME/Desktop/test_plugin

> 3. Install bundle by using command:   devel install /Users/USER_NAME/Desktop/test_plugin

# Sample Input

  * This bundle will take four input file

> 1. testingList_Stride.txt (path: test_plugin/ChimeraX/data/). The testing data
> information will be list in this file.

> 2. testingList.pt (path: test_plugin/ChimeraX/data/)

> 3. model.chkpt (path: test_plugin/ChimeraX/)

> 4. pdb and mrc (path: test_plugin/ChimeraX/data/EMDBdata_6/)

# Run this bundle

Use the below command to run the bundle:
```
testdl
```
You may check "testdl.log" (typically under the directory of './ChimeraX/') to track the running status. This basically will take more than five
minutes.

# Sample output file

The result can be found from "./ChimeraX/output/labels" and "./ChimeraX/output/visuals".

For a smaple output, it can be found in the directory of ./ChimeraX.

# Contact Me
Email: ymu004@odu.edu

