# Website Development

[![image](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/HeZhang1994/HeZhang1994.github.io/blob/master/LICENSE)
[![image](https://img.shields.io/badge/lagrange-html5-blue.svg)]()
[![image](https://img.shields.io/badge/status-stable-brightgreen.svg)]()

This is an **HTML** implementation of developing personal website with **GitHub.io**.

Many thanks to [TEMPLATED](http://templated.co) for providing the source template of this website (see `SourceTemplate_privy/`).

## Contents

- `default.css` - The CSS file that defines the characteristics of the website.

- `index.html` - The HTML file of the home page of website.

- `hz***.html` - The HTML file of the child page of website.

- `baidu***.html` - The verification file of website on Baidu search engine.

- `google***.html` - The verification file of website on Google search engine.

## Website Configuration and Establishment

The following procedures for setting up a website with **GitHub.io** are partly recapitulated from [here](https://pages.github.com/). For detailed information of how to use `git`, see the [online tutorial](https://chryswoods.com/beginning_git/) provided by [Christopher Woods](https://github.com/chryswoods).

1. Configure your GitHub client on local computer.
```bash
$ git config --global user.email "xxx@xxx.xxx"
# Replace 'xxx@xxx.xxx' with your GitHub login email.
# E.g., $ git config --global user.email "hz@gmail.com".

$ git config --global user.name "aaa"
# Replace 'aaa' with your GitHub user name.
# E.g., $ git config --global user.name "hezhang".
```

2. Create a public repository called `aaa.github.io` on GitHub, where `aaa` is your GitHub user name. You can now use website templates provided by GitHub, or continue the establishment and use other templates later.

3. Clone `aaa.github.io` repository to local computer in Terminal.
```bash
$ git clone https://github.com/aaa/aaa.github.io
```

4. Add some contents to the website (this will create `index.html`) in Terminal.
```bash
$ cd aaa.github.io
~$ echo "Hello World" > index.html
~$ git add --all
~$ git commit -m "Initial commit"
~$ git push -u origin master
```

5. After a few minutes, open https://aaa.github.io/ on browser and you will see "Hello World" on the website.

6. Now you can develop the website by editing/creating `default.css`, `index.html`, and other HTML/CSS files.

## Website Verification on Google Search Engine

Verifying a website on search engines provides you the ownership to this website. The following procedures show how to verify the website https://aaa.github.io/ on Google search engine.

<img src="https://github.com/HeZhang1994/HeZhang1994.github.io/blob/master/images/Website_GoogleVerification.gif" height="350">

1. Open [Google Search Console](https://search.google.com/search-console/about) and log in with your Google account.

2. Click the drop-down arrow on the top-left corner and then click "+ Add property" button.

3. Type `https://aaa.github.io/` in the input box of "URL prefix" page and then click "CONTINUE" button.

4. Download the verification file `google***.html` and upload it to `aaa.github.io` repository on GitHub.

5. Go back to the verification page. Wait a few minutes and click "VERIFY" button.

6. Verification on Google search engine has accomplished.

<!--
### Baidu Search Engine
1. Open [Baidu Resource Platform](https://ziyuan.baidu.com/) and log in with Baidu account.
2. Click "Add Website" and complete user information (if required).
3. Type __https://aaa.github.io__ in the input box and click "NEXT".
4. Select website attribute (e.g., Information Technology).
5. Select verification method - document verification.
6. Download the verification file `baidu_verify***.html` and upload it to your GitHub.io repository.
7. Go back to the verification page. Wait a few minutes and click "COMPLETE VERIFICATION".
8. Complete verification on Baidu search engine!
-->

## Useful Links

* Online HTML and CSS editor - [CodePen](https://codepen.io/)

* Online picture resizer - [Picresize](http://www.picresize.com/)

* Online picture format converter - [Online-Converter](https://www.online-convert.com/)

* [CSDN Blog](https://blog.csdn.net/renfufei/article/details/37725057)

<br>

<i>Please star this repository if you found its content useful. Thank you very much. ^_^</i>

<i>如果该程序对您有帮助，请为该程序加星支持哈，非常感谢。^_^</i>
