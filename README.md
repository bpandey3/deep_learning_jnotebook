# learning JHUB



#### Change to course folder

```
cd zero_to_deep_learning_video
```

#### Create the course environment

```
conda env create
```

wait for the environment to create.

#### Activate the environment (Mac/Linux)
```
conda activate ztdl
```

#### Activate the environment (Windows)
```
conda info --envs
Output:

base                  *  /opt/anaconda3
ydata_env                /opt/anaconda3/envs/ydata_env
                         /opt/miniconda3
                         /opt/miniconda3/envs/mlnotes
                         /opt/miniconda3/envs/ztdl
                         /opt/miniconda3/envs/ztdltest

conda activate  /opt/miniconda3/envs/ztdltest

```

Check that your prompt changed to

```
(ztdl) $
```

#### Launch Jupyter Notebook

```
jupyter notebook
```

#### Open your browser to

```
http://localhost:8888
```

#### Run the Check environment Notebook

Go to the course folder, open the notebook `0_Check_Environment.ipynb` and run it. If you see the message:

    Houston we are go!

You are good to go! Enjoy!


#### Troubleshooting installation
If for some reason you don't see `Houston we are go!`, the simplest solution is to delete the environment and start from scratch again.

To remove the environment:

- close the browser and go back to your terminal
- stop jupyter notebook (CTRL-C)
- deactivate the environment (Mac/Linux):

```
conda deactivate
```

- deactivate the environment (Windows 10):

```
deactivate ztdl
```

- delete the environment:

```
conda remove -y -n ztdl --all
```

- restart from environment creation and make sure that each steps completes till the end.

#### Updating Conda

One thing you can also try is to update your conda executable. This may help if you already had Anaconda installed on your system.

```
conda update conda
```