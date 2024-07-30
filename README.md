# Applied-Statistics-Project

This repository holds my project from my Applied Statistics class. The project was to determine if any discrimination was found in the California Department of Defense. R was used for the analysis of the [California_DDS_Expenditures.csv]() file. Instructions on how to use the R file to duplicate this analysis is located below.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Program-Overview](#program-overview)

## Installation

You need [R](https://rstudio-education.github.io/hopr/starting.html) for this project, [RStudio](https://rstudio-education.github.io/hopr/starting.html) is recommended.

### Option 1: using [git](https://git-scm.com/downloads)
1. Clone the repository:

    ```sh
    git clone https://github.com/LucasHasting/Applied-Statistics-Project.git
    ```

2. Navigate to the project directory:

    ```sh
    cd Applied-Statistics-Project
    ```
    
### Option 2: without git
1. Download the project as a zip file
2. [Extract the zip file](https://www.wikihow.com/Unzip-a-File)
3. go to the command line and run the following:
   ```sh
   cd /path/to/files
   ```

#### Run from the command line
1. go to the command line and run the following:
   ```sh
   Rscript Project.R
   ```
2. All graphs are located in the project folder in the Rplots.pdf file

#### Run from RStudio
1. Click File (located at the top left) -> Open File
2. Open Project.R
3. Click Session (located near File) -> Set Working Directory -> To Source File Location
4. Click where the script is
5. Click ctrl (cmd on mac) + a
6. Click the run button (located at the top below the tabs)
7. The graphs are located at the bottom right, the left and right arrows can be used to select a graph

## Usage

The main purpose of the R script is to subset the data in [California_DDS_Expenditures.csv](https://github.com/LucasHasting/Applied-Statistics-Project/blob/main/Discrimination%20in%20the%20California%20Department%20of%20Defense.pdf) and to generate graphs based on the subsetted data, the graphs can be found in the [Discrimination in the California Department of Defense.pdf](https://github.com/LucasHasting/Applied-Statistics-Project/blob/main/Discrimination%20in%20the%20California%20Department%20of%20Defense.pdf) paper.

## Example

### CMD
![EXAMPLE](examples/example1.png)
![EXAMPLE](examples/example2.png)

### RStudio
![EXAMPLE](examples/example3.png)

## Program-Overview

[Project.R](https://github.com/LucasHasting/Applied-Statistics-Project/blob/main/Project.R): contains the R script used in the paper.  
