1) Install docker
2) Add this dockerfile somewhere on your PC 
3) Run the commands: <br>
  docker login cgc-images.sbgenomics.com <br>
  docker build -t cgc-images.sbgenomics.com/<username>/fastqc:0.11.8 . <br>
  docker push cgc-images.sbgenomics.com/<username>/fastqc:0.11.8
