---
layout: post
title:  "Bash Tips"
date:   2022-05-29 17:35:00 +0900
categories: bash
---

### Find only files

    find ./ -type f

### Move current folder files to subdirectory

    mkdir -p subd
    find . -type f -maxdepth 1 -exec mv {} ./subd/ \;
