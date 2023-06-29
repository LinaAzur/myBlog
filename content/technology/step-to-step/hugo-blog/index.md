---
title: "How to do a hugo blog and not die while trying"
description: "Yo will learn how to do a hugo blog and publish it with github pages"
---

## 1.- Make sure you have a gtihub account

## 2.- Choose the theme your going to use
You need to choose your theme from hugo blog: https://themes.gohugo.io/

## 3.- Fork the theme of your preference in your repositories
This will allow you to have the copy all the time in your repositories, you don't have to worry if for any reason the original repo disapears.

## .- Create a new folder/repository
In case you already have the folder where you going to have your blog, then you just have to create the repository and connect it with the origin repository

In case you haven't created anything, you need to create the repository in github and then clone it in your local.

## Myblog/
Inside this folder, we need to follow the instructions of the quickstart from hugo blog
alongside with the instructions of the theme that you choose. You have to have a structure like this:


Where *theme/* will contain the submodule of the theme that you fork in your repositories

## .- Configure your config.toeml
This will depend entirely on the theme that you choose, make sure you read carefully the configuration part 

## Usually your fisrt post should be inside content/posts/
I recommend that you create a test post, don't forget you need to use .md as extention file

## You should be able to use hugo servee to compile your blog and visualize it as you want


## Now here it comes the funny part
You need to create another repository, with the exact same name as your profile, but we're add .gihub.io at the end, in my case the repository name will be Jucaski.github.io This will also be your personal url where your blog will be deploy
