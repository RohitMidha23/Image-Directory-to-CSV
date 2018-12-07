# Image Directory to CSV

Often times we need to convert our dataset of images to CSV files. This does just that. 

## Setup 

1. Clone this repository. 
2. Show some :heart: by :star:ing this repo
3. Add the path of the directory you want to convert in 
```python
myFileList = createFileList('/path_to_directory_with_images/') 
```
4. Name the csv file to be created in 
```python
with open("name_you_want.csv", 'a') as f: 

``` 
5. In case you're not able to locate the .csv file, search it up with the name given. 
