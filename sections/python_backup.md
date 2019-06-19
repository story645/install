 [Anaconda](https://www.anaconda.com/download/) is a distribution of Python. It provides a Python programming environment, the Jupyter notebook environment, and the [conda](conda.md) package management system. 

## Download Python 3.+: 

1. Download Anaconda at:  https://www.anaconda.com/download/ 
 
2. *Click* on the Python 3.+ button:

![Anaconda download webpage with 3.6 button highlighted](../images/windows/anaconda/anaconda00.png)

3. You can ignore this. Just close this screen and wait for your donwload to finish.

![Anaconda thank you image](../images/windows/anaconda/anaconda01.png)

## Install

1. *Click* on the installer file you just downloaded:

2. You should see the initial install screen. *Click* `Next`:
 
 ![initial installation image](../images/windows/anaconda/anaconda02.png)

3. Accept the license by *clicking* `I Agree`:
 
![licence agreement](../images/windows/anaconda/anaconda03.png)

4. Install Anaconda only for yourself by choosing the just for me radio button. *Click* `Next`:

![radio menu, select the 1st "just me" option](../images/windows/anaconda/anaconda04.png)

5. Choose the location to install anaconda (the default is fine). *Click* `Next`:

![text box with path for default Anaconda install and browse button ](../images/windows/anaconda/anaconda05.png)

6. On the Advanced Installation Options page, select **both check boxes**: "Add Anaconda to my PATH environment variable" and "Register Anaconda as my default Python". Then *click* `Next`: 

![advanced installation options window. Has two check boxes: Add anaconda to PATH environment variables, and `Register Anaconda as my default Python`](../images/windows/anaconda/anaconda06.png)

7. The installation may take a while, so go grab a snack or check your email: 

8. When finished, the window will list the location of the Anaconda installer. *Click* `Next`:

![Full progress bar and printed output listing location of Anaconda files](../images/windows/anaconda/anaconda07.png)

9. *Click* `Install Microsoft VSCode`. If it is already installed, *click* `Skip`:

![menu option to also install vscode](../images/windows/anaconda/anaconda8.png)

10. This is the final window. You can uncheck all the boxes and *Click* `Finish`:

![final installation window for anaconda, has two check boxes: learn more and learn how to get started](../images/windows/anaconda/anaconda09.png)

## Test

Open a [windows](windows_terminal.md) or [OS/X](osx_terminal.md) terminal and type `python`. The terminal should print something like:
* OS/X:
    ```python
    Python 3.6.3 |Anaconda, Inc.| (default, Dec  5 2017, 17:30:25) 
    [GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>> 
    ```
* Windows: 

    ```python
    Python 3.6.5 |Anaconda, Inc.| (default, Mar 29 2018, 13:32:41) [MSC v.1900 64 bit (AMD64)] on win32
    Type "help", "copyright", "credits" or "license" for more information.
    >>> 
    ```

Type `exit()` to leave python

## References ##

* [Anaconda Cheet Sheet](http://conda.pydata.org/docs/using/cheatsheet.html)

* [Jupyter Reference Sheet](https://damontallen.github.io/IPython-quick-ref-sheets/)

