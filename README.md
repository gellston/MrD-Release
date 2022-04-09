<center>
<img src="https://github.com/gellston/MrD-Release/blob/main/Images/MrDLogo.png?raw=true" width=200></img> 
</center>

MrD
=======================

MrD is a free image labeling and training tool developed in C# WPF based on Visual Studio 2022 <br/>
The current version supports labeling classification datasets and training, auto labeling.

Development Environment
=======================
 - **Visual Studio 2022**
 - **Microsoft .NET 6**

Download
=======================

- <a href="https://github.com/gellston/FIAT-Release/releases/download/0.6/FIAT.exe" target="_blank">FIAT Labeling tool download</a>
- <a href="https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.2-windows-x64-installer" target="_blank">.NET6 framework</a>

DEMO
=======================
- Classification Training

https://user-images.githubusercontent.com/42884297/162553818-eaeb209f-0cde-43d7-933a-e475a8a5f5d1.mp4




- Classification Auto Labeling

https://user-images.githubusercontent.com/42884297/162554135-2095cba4-5488-4ce9-8792-6edfcc2a0a09.mp4



Shortcut Key
=======================
| Shortcut Key | Function |
|---|---|
| <kbd>F1</kbd> ~ <kbd>F12</kbd> | ***Label the image with the target label at that index*** |
| <kbd>Ctrl</kbd> + <kbd>S</kbd> | ***Save all label information*** |
| <kbd>Ctrl</kbd> + <kbd>O</kbd> | ***Open image folder*** |
| <kbd>Up</kbd> | ***Previous image*** |
| <kbd>Down</kbd> | ***Next image***  |


Strcture
=======================
### Classification
<img src="https://github.com/gellston/FIAT-Release/blob/main/snapshoot/snapshot1.jpg?raw=true"></img>

- __target_info.json 
    - File containing representative label information
```json
[
    {
        "Color":"#FFFF0000",
        "Name":"Bread"
        
    },
    {
        "Color":"#FF008000",
        "Name":"Pizza"
        
    },
    {
        "Color":"#FFFFFFFF",
        "Name":"Hamburger"
        
    },
    {
        "Color":"#FFF79646",
        "Name":"Chicken"
        
    }
]
```

- (each file).json 
    - A file containing user-labeled information about an image.
```json
{
    "FileName":"1_1_bread.jpg",
    "FilePath":"C:\\Users\\Fiat\\Desktop\\food\\1_1_bread.jpg",
    "ClassCollection":[
        {
            "Color":"#FFFF0000",
            "Name":"Bread"
            
        }
    ]
    
}
```




<div style="text-align: right; margin-right:30px;"> 

[TOP](#vision-studio) 

</div>

```
The MIT License (MIT)

Copyright (c) 2022-present FIAT Development Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
<div style="text-align: right; margin-right:30px;"> 

[TOP](#vision-studio) 

</div>
