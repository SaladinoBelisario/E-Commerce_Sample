# **`MEAN Fullstack E-Shop`**

This is the Monorepo for the MEAN E-Shop application. This Monorepo has been divided with Git 
submodules, so if you want to fetch the whole project you need to configure or tell Git to fetch
submodules.

The backend also uses Git LFS for the Sample images, so make sure you have installed Git LFS for 
you to fetch the images.

Technologies used:

[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=101010)]()
[![MongoDB](https://img.shields.io/badge/Express-47A248?style=for-the-badge&logo=express&logoColor=white&labelColor=101010)]()
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white&labelColor=101010)]()
[![NodeJS](https://img.shields.io/badge/NodeJS-339933?style=for-the-badge&logo=node.js&logoColor=white&labelColor=101010)]()

# **Important**

The backend module expects to find a _.env_ file in this directory, so write your environment
variables here.

> _Example .env file_
>
> API_URL=your/base/api/url
>
> DB_NAME=YOUR_DB_NAME
>
> DB_USER=DB_SAMPLE_USER
>
> DB_PWD=DB_SAMPLE_PASSWORD
>
> JWT_SECRET=yourSecret

The instructions for deploying the backend and frontend are in the corresponding submodules.