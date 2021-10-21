![enter image description here](https://i.imgur.com/Pkn5quX.jpg)
# Scrabble Assistant (29)

## Github Link:
https://github.com/Digital-Image-Processing-IIITH/project-fmss

## Team Name : fmss
### Fanish Jain
### Swastik Murawat
### Swati Dantu
### Mayank Goyal

## Main Goals

The main goal of the project is to create an image processing software which will convert an image of a Scrabble board to a matrix of characters (as present in the image).

This matrix then can be further used for several purposes such as :

Backend for Scrabble AI applications, Hint generation, Live Score, and for fun.

## Problem Definition

Scrabble is a commonly played word game in which players take turns forming words using a set of seven letter tiles and placing them onto a grid, following placement rules similar to a crossword puzzle. For further reading about scrabble , 
read https://en.wikipedia.org/wiki/Scrabble.

We propose creating a software using image processing tools which identifies the current board state from a single image of the Scrabble board.

Our software will be able do the following :

1.  Account for small amounts of blurring during image capture
    
2.  Identify tiles within the input image, even if the image is subjected to perspective skew, rotation, and scale. (However the skew angle would affect beyond a particular angle)
    
3.  Extract letters from the tiles. (Character Recognition)
    
4.  Superimpose a grid on the Scrabble board
    
5.  Current score and Hint generation (Optional , will do if time left)
    

How will this problem be solved ?

General steps/algorithm , subject to change along the course of the project.

1.  Account for the blur, perspective skew during image capture
    
2.  Tile Size Estimation and Normalization
    
3.  Grid detection and formation
    
4.  Character Detection
## Result Of the Project

We expect our software to correctly detect the characters on the board and output the character matrix with high accuracy (accuracy is the most important factor because it determines the score and affects the hint generation).

## Milestones and Expected Timeline

![Timeline](./images/timeline.jpg)

### Project Core

#### 1) Tile Size Estimation and Normalization

#### 2) Grid Detection

#### 3) Grid Fitting

#### 4) Perspective Skew Correction

#### 5) Character Detection

#### 6) Character Recognition

### Filtering Out Input

#### 1) Noise Reduction

#### 2) Blurring Removed

#### 3) Unwanted Background Removal

### Additional Functionalities(Will try if all above gets done)

#### 1) Find out the words which the player can form given the state of game.

#### 2) Sort all the words by their score in the descending order.

