# CV_template
Here is an Academic CV template created by Liaoyi Xu.
# Motivation
I created this template as managing content as well as format in Microsoft - word was so hard since it had to be update very frequency and applied in multiple places. The content of most available CV templates is either so crowded or too "fancy" therefore hard for other people to focus on. I personally prefer this simple structure CV and easier for people find key points.
# Download PDF version of this template here
[CV_template.pdf](https://github.com/t3isuan/CV_template/files/6215439/CV_template.pdf)
# How to use?
### For local compile users:
1. Download this repo ```git clone https://github.com/t3isuan/CV_template.git``` 
2. Open ``CV_template.tex`` with some text editor (VS Code, Sublime Text, etc.)
3. Compile ``CV_template.tex`` directly. 
(Please make sure your computer has already installed LaTex and corresponding extensions)
### For Overleaf users:
1. Download this repo (same as **For local compile users**)
2. Compile the folder ``CV_template`` to zip file
3. Go to https://www.overleaf.com/project -> click 'New Project' -> click 'Upload Project' -> drag CV_template.zip (which you have compressed in step 2) to 'Upload Zipped Project' box
4. Open ``CV_template.tex``, edit line 18-20 as following:

Original:
```latex
\usepackage{fontspec}                 % for local compile
\setmainfont{Times New Roman}         % for local compile
%\usepackage{times}                   % for Overleaf
```
Changed to:
```latex
%\usepackage{fontspec}                % for local compile
%\setmainfont{Times New Roman}        % for local compile
\usepackage{times}                    % for Overleaf
```
5. Compile
# License
Format is MIT but all the data is owned by Liaoyi Xu.
