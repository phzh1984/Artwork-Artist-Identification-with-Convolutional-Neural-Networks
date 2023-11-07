# Artwork-Artist-Identification-with-Convolutional-Neural-Networks

Overview

This repository contains an implementation of a convolutional neural network (CNN) for artist identification using a dataset of artworks from 11 influential artists. The goal is to develop an algorithm that accurately identifies the artist behind a given painting.

Dataset

The dataset includes images of artworks from 11 artists, with varying numbers of paintings per artist. As the dataset is imbalanced, only the paintings from these 11 artists were selected to facilitate better training and computation efficiency. The images are available in the 'resized.zip' file, which contains resized versions of the original artworks.

artists.csv: Dataset providing basic information for each artist.

images.zip: Collection of full-size images, organized in folders and sequentially numbered.

resized.zip: Same collection as 'images.zip', but with resized images extracted from the folder structure for faster processing.

The data was scraped from artchallenge.ru around February 2019.

Objective

The primary objective is to develop an algorithm that can identify the artist behind a given painting. The model utilizes Convolutional Neural Networks to recognize artistic styles based on color usage and geometric patterns present in the images.

Inspiration

This project was inspired by a challenge to use machine learning techniques to identify artists' works, providing a tool to discern the creator of a given painting.
