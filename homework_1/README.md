1) Install docker
2) Add this dockerfile somewhere on your PC 
3) Run the commands:
  docker login cgc-images.sbgenomics.com
  docker build -t cgc-images.sbgenomics.com/<username>/fastqc:0.11.8 .
  docker push cgc-images.sbgenomics.com/<username>/fastqc:0.11.8
