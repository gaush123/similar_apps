# similar_apps
Finding out similar apps for a given app using description of the apps

To replicate results using vanilla python use 'requirments.txt' file

To replicate results using anaconda run: 
- `conda env create -f similarapps.yml`

To load mongo collection
- run `unzip apps.zip` to load collection backup
- run `mongorestore --host=<hostname> --db=apps <path_to_unzipped_apps_file>`

**Description extractor**: app_info_extractor.ipynb

**Approach 1 & 2 using TF-IDF**:  similar_apps_preprocessing-tf-idf.ipynb

**Approach 3 using word2vec**:  word_to_vec_approach.ipynb

- One will also need to download word2vec file (https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit) to be able to vectorize function
