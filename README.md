# Big Bee Image Sequence Generator

This repository helps to generate image sequence of specimen following Big Bee image sequence naming conventions.

## Usage


```
./create-imageseq [catalog number] [dwca URL]
```


where 

`catalog number` is the catalog number of the specimen you'd like to generate an image sequence for.

and

`dwca URL` is location of the Darwin Core Archive that includes a specimen with the catalog number 

## Results

If found, image sequence data products will be available in folder `dist/[catalog number]/` . 


## Example

```
./create-imageseq "UCSB-IZC00012194" "https://library.big-bee.net/portal/content/dwca/UCSB-IZC_DwC-A.zip"
```

generated:

find dist

 
