<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="http://www.dsg.nutn.edu.tw">
    <img src="definitions/DSL_shark.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">國立臺南大學碩士論文LaTeX</h3>

  <p align="center">
    我把論文都放在那裡了，自己去找吧！！
    
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#About">About The Project</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#remark">Remark</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

因為林朝興　老師要求DSG實驗室學生使用LaTeX編輯碩士論文，並且先前學長姊留下的LaTeX所編譯出的文件存在bugs。由DSG實驗室學生修改過後，將編譯器由PDFLatex改為XeLatex，並且修正中文粗體的問題，而產生了此版本的LaTeX。此版本產生的碩士論文，在110年第二學期提交到國立臺南大學圖書館以及資工系都沒有問題。



<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started
### Prerequisites

請先安裝**編譯器**與**編輯器**
* **編譯器** **MikTex** [https://miktex.org/download](https://miktex.org/download)
* **編輯器** 推薦使用**TexStudio** [https://www.texstudio.org/](https://www.texstudio.org/)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
1. clone this repository
2. 開啟```content/definitions.tex```修改中英文論文題目、中英文關鍵字、提交日期、研究生中英文姓名、指導教授中英文姓名以及致謝年月
3. 開啟```content/frontpages/封面.doc```，依照學校規定製作論文封面，記得加上<span style="color: red;">**正確浮水印**</span>，並且另存成```front.pdf```
4. 開啟```content/frontpages/書名頁.doc```，依照學校規定製作書名頁並且另存成```bookname.pdf```
5. 開啟```content/frontpages.tex```，編輯中、英文摘要以及致謝，請好好感謝該感謝的人
6. 開啟```content/main.tex```，開始寫論文內容囉！！！



<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Remark
1. 編譯器請選擇**XeLaTex**，建議從上方工具列```Options -> Configure TexStudio... -> Build```，將Default Compiler修改為**XeLaTeX**
2. 請將所有參考書目，放在```content/ref.bib```，此檔案可透過[JabRef](https://www.jabref.org/)或是[Mendeley](https://www.mendeley.com/)產生

## Reference
* [DSG LaTeX教學文件](http://www.dsg.nutn.edu.tw/LaTex_PAGE/)
* [國立臺南大學 博碩士論文系統](https://cloud.ncl.edu.tw/nutn/)
* [國立臺南大學 研教組](http://academic.nutn.edu.tw/index.php)