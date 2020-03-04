# **Clumsy-Bird**

A "Flappy Bird" clone made with MelonJS.

[![Github](https://img.shields.io/badge/Credit-Github-black)](https://github.com/ellisonleao/clumsy-bird)

Try online at http://kiplikipli.my.id

# Contents

- [1. Contents](#contents)
- [2. About](#about)
- [3. Run Locally](#run-locally)
- [4. Installation in Virtual Machine](#installation-in-virtual-machine)

# About

# Run Locally

> 1. Install Node, NPM, and Grunt
> 2. Clone https://github.com/ellisonleao/clumsy-bird/
> 3. Get inside the directory
> 4. Run npm install for installing dependencies
> 5. Run grunt connect
> 6. Open your browser at http://localhost:8100
> 7. Play the game!

# Installation in Virtual Machine

### Using Ubuntu Server

**Pre-requisites :**

> 1. Virtual Box, you can download [here](https://www.virtualbox.org/wiki/Downloads)
> 2. Ubuntu Server, you can download [here](https://ubuntu.com/download/server)
> 3. Web Server ( ex. Apache or NGINX )

**Steps :**

1. Install web server, in this case i'm using Apache2
   > `sudo apt-get install apache2`
2. Get into apache2 root folder in /var/www/html
   > `cd /var/www/html`
3. Clone the Clumsy Bird Github repository
   > `git clone https://github.com/ellisonleao/clumsy-bird/`
4. Change the apache2 root folder to a folder that you have cloned before
   > `sudo nano /etc/apache2/sites-enabled/000-default.conf`
   >
   > **From this**  
   > ![Before](Before.png)  
   > **To this**  
   > ![After](After.png)
   >
   > **Explanation**
   >
   > Change the DocumentRoot path to the Clumsy-Bird directory
5. Do the same thing as 4, but the sites-available one
   > `sudo nano /etc/apache2/sites-available/000-default.conf`
6. Restart Apache2
   > `sudo service apache2 restart`
7. Open localhost:**port** in your host pc, where **port** is the port that you have already set while you set the virtual machine
   > ![Game](Game.png)
8. Play the game!

# Kustomisasi

Memainkan versi yang berbeda dengan tampilan yang berbeda dari versi biasa dapat memberikan pengalaman dan kesenangan baru bagi pengguna.
kostumisasi tersebut mungkin dilakukan dengan asset yang kamu miliki, berikut adalah daftar dari asset yang digunakan pada game ini. Kamu hanya perlu menggantinya dengan apa yang kamu inginkan. Hanya perlu ingat nama dan ukuran yang diperlukan.

- [bg.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/bg.png) - Size: `900x504px`. Tampilan background yang digunakan pada game.
- [clumsy.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/clumsy.png) - Size: `255x60px` . Gambar animasi dari burung dalam game. Terdapat 3 frame animasi.
- [gameover.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/gameover.png) - Size: `245x132px`. Logo gameover di dalam game.
- [gameoverbg.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/gameoverbg.png) - Size: `505x361px`. Kotak background saat gameover yang digunakan untuk tampilan skor.
- [getready.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/getready.png) - Size: `405x134px`. Pesan saat memulai game.
- [ground.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/ground.png) - Size: `900x96px`. animasi permukaan tanah dalam game.
- [logo.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/logo.png) - Size: `351x145px`. Logo dari game.
- [new.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/new.png) - Size: `48x48px`. Notifikasi saat pengguna mencapai skor tertinggi yang baru.
- [pipe.png](https://raw.githubusercontent.com/ellisonleao/clumsy-bird/gh-pages/data/img/pipe.png) - Size: `148x1664px`. Pipa yang digunakan untuk menapilkan rintangan secara random.
