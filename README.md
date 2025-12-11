<center>
<img src="https://github.com/gellston/MrD-Release/blob/main/Images/MrDLogo.png?raw=true" width=200></img> 
</center>


MrD
=======================
MrD is a free image labeling and training tool developed in C# WPF based on Visual Studio 2022 <br/>
The current version supports labeling classification datasets and training, auto labeling.

MrD WIKI
=======================
[[https://MrDTeam.com](https://www.notion.so/gellston/Mr-D-WIKI-831813f65c0646838e224cb64f455f4f)](https://www.notion.so/gellston/Mr-D-WIKI-831813f65c0646838e224cb64f455f4f)


Donation
=======================
<a href="https://buymeacoffee.com/wantrnqhdgx" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

Development Environment
=======================
 - **Visual Studio 2022**
 - **Microsoft .NET 6**

Download
=======================

- <a href="https://github.com/gellston/MrD-Release/releases" target="_blank">MrD download</a>
- <a href="https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.2-windows-x64-installer" target="_blank">.NET6 framework</a>
- <a href="https://developer.nvidia.com/cuda-11.3.0-download-archive" target="_blank">CUDA 11.3 for GPU Training</a>



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

License
=======================

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

Poster
=======================
<center>
<img src="https://github.com/gellston/MrD-Release/blob/main/Images/poster.gif?raw=true"></img> 
</center>

<div style="text-align: right; margin-right:30px;"> 

[TOP](#vision-studio) 

</div>
