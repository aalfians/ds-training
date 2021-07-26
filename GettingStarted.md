# Introduction

Pada workshop ini kita akan mengekplorasi kemampuan Data Science untuk mengambil *insight* dari data. Tetapi sebelumnya, *make sure* kita menggunakan tools yang tepat untuk memulai pembelajaran.

Tutorial pendek ini membahas tentang :
+ Alternatif *platform* yang bisa digunakan.
+ Konfigurasi komputer lokal untuk pembelajaran data science
+ Menggunakan Scikit-learn, termasuk instalasi.

# Platform

## Google colab

Agar dapat menjalankan script program yang diberikan pada pelatihan ini, kita bisa menggunakan Python yang terinstall secara *local* di komputer ataupun secara *online* dengan menggunakan infrastruktur cloud seperti misalnya google colab. Penggunaan cloud memudahkan kita untuk secara langgung menggunakan fasilitas yang digunakan dalam pembelajaran data science (Python, pandas, matplotlib, sklearn ... ), tanpa melalui tahap instalasi. Kita bisa langsung bisa menggunakannya hanya dengan melakukan log-in ke penyedia cloud dari mana saja tanpa perlu secara fisik berada di posisi yang sama dengan komputer yang kita gunakan. Beberapa penyedia fasilitas cloud ini bahkan menyediakan sarana komputasi yang cukup *powerful* yang bisa kita gunakan, seperti misalnya penggunaan GPU sebagai akselerator di node komputasi yang kita gunakan. Meski memberikan fasiltas yang cukup baik untuk analisis data, biasanya penyedia cloud tetap memberi batasan tertentu ada node yang kita gunakan, seperti durasi koneksi, ukuran memori dan storage. Selain itu, untuk tetap bisa menggunakan fasilitas cloud kita juga harus selalu terhubung dengan internet.

 ## Python local

Instalasi Python dan package-package pada komputer local yang kita miliki juga bisa dilakukan untuk memenuhi kebutuhan komputasi kita dengan menggunakan device yang sudah tersedia. Instalasi secara local ini juga membebaskan kita dari keharusan untuk selalu terkoneksi pada jaringan internet dan juga batasan-batasan yang ada di fasilitas komputasi cloud.  

# Installations and configurations

1. *Install Python.* Ensure that Python is installed on your computer. You will use Python for many data science and machine learning tasks. Most computer systems already include a Python installation. There are useful Python Coding Packs available as well, to ease the setup for some users.

> Some usages of Python, however, require one version of the software, whereas others require a different version. For this reason, it's useful to work within a virtual environment.

2. *Install Visual Studio Code.* Make sure you have Visual Studio Code installed on your computer. Follow these instructions to install Visual Studio Code for the basic installation. You are going to use Python in Visual Studio Code in this course, so you might want to brush up on how to configure Visual Studio Code for Python development.

> Get comfortable with Python by working through this collection of Learn modules

3. *Install Scikit-learn, by following these instructions.* Since you need to ensure that you use Python 3, it's recommended that you use a virtual environment. Note, if you are installing this library on a M1 Mac, there are special instructions on the page linked above.

4. *Install Jupyter Notebook.* You will need to install the Jupyter package.

# Notebooks

Selama pelatihan ini, kita akan banyak menggunakan *notebooks* yang bisa dijalankan baik menggunakan Jupyter di komputer local, Google colab ataupun binder. Notebooks merupakan tools yang powerful untuk belajar dan berlatih data science maupun machine learning dengan menggabungkan code executable dengan content naratif modern (HTML, image, equations dalam LaTeX). Colab yang disediakan oleh Google memungkinkan eksekusi notebooks di cloud secara grastis, tanpa perlu instalasi dan bahkan memungkinkan kita memanfaatkan kekuatan yang dipunyai oleh [GPUs](https://en.wikipedia.org/wiki/Graphics_processing_unit).

Notebooks bukanlah merupakan web page static, melainkan satu environtment interaktif yang memungkinkan kita melakukan penyusunan code program pada satu *cell* dan mengeksekusinya secara langsung untuk melihat hasilnya. 

# Your ML authoring environment
You are going to use notebooks to develop your Python code and create machine learning models. This type of file is a common tool for data scientists, and they can be identified by their suffix or extension .ipynb.

Notebooks are an interactive environment that allow the developer to both code and add notes and write documentation around the code which is quite helpful for experimental or research-oriented projects.
