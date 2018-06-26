
## Resources
* **Training slides**: https://galaxyproject.github.io/dagobah-training/2018-gccbosc/
* http://bit.ly/galaxyadmin
* **Jetstream computing resources**: http://bit.ly/adminvms/
  + login: `ssh ubuntu@149.165.156.80`, password is in the email.
* **http://bit.ly/adminchat**
* **Galaxy Server administration**: http://galaxyproject.github.io/training-material/topics/admin/


## Build conda receipe for fleeqtk from scratch

* step 1: git clone bioconda: `git clone https://github.com/bioconda/bioconda-recipes.git`
* step 2: make a copy of seqtk receipe from bioconda and edit it to create the fleeqtk receipe.
  + edit meta.yml file
  + edit buid.sh file
* step 3: run `conda build .`
