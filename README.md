# Data Justice Package

1. First make sure you have the most recent version of pip.

```
python3 -m pip install --upgrade pip
```

2. Install the data_justice package with the commands bellow.

```
# If you are working in jupyter:
!pip install -i https://test.pypi.org/simple/ pg-ethics==0.0.1
```



```
# If you are working in the terminal:
pip install -i https://test.pypi.org/simple/ pg-ethics==0.0.1
```

3. Once the package has been installed successfully, run the command below in your notebook or terminal.

```
from data_justice import data_justice
```

4. To print the generate the data_justice agreement run:



```
data_justice.generate_agreement()
```

5. This function call will print out the data_justice agreement in markdown format.

6. Copy the agreement and paste it into a markdown cell.

7. Follow the steps in the agreement!
