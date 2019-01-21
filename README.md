# kaggle-template
Template to quickly get started on Kaggle competitions. 

**To get started:**
```
git clone https://github.com/alhankeser/kaggle-template my-kaggle-competition
python3 -m virtualenv env
source env/bin/activate
pip install -r requirements.txt
cd input
kaggle competitions download -c kaggle-competition-slug
rm -rf .git
git init
git remote set-url origin https://github.com/my-username/my-repo
git push -u origin master
cd ../notebooks
jupyter notebook
```
