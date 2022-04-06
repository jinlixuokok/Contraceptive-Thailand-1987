# starter_folder

This repo contains the necessary file and output results of Further Data Analysis Project based on TDHS, 1987

It is organised as follows:

input:/

  data:/
  
    datasheet_template.rmd: The appendix of this project, written in R
    
    datasheet_template.pdf: Knited PDF of appendix
    
    raw_data.csv: the raw data directly read from TDHS PDF
    
    reference_datasheet.bib: reference list used in the appendix
    
  literature:/
  
    Thailand DHS.pdf: the original TDHS file used for study
    
output:/

  data:/
  
    cleaned_data.csv: the data cleaned and processed from raw data
    
    raw_data.csv: the raw data directly read from TDHS PDF
    
  paper:/
  
    TDHS Analysis project.RMD: the final Rmarkdown document of this project, contains all necessary R code.
    
    TDHS Analysis project.Pdf: pdf version knited for this project
    
    ref_list.bib: contains all the references
    
scripts:/

    00-simulation.rmd: simulator of data used for the dataset which was planned to be used
  
    01-gather_data.rmd: used R to first read and draw data from the datasheet in TDHS
  
    02-clean_and_prepare_data.rmd: cleaned and grouped the raw data, replaced all typos and mistakes, save as cleaned_data.csv
 
