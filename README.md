import zipfile
import os

zip_path = "/mnt/data/pan11-author-identification-corpora.zip"
extract_path = "/mnt/data/pan11"

with zipfile.ZipFile(zip_path, 'r') as zip_ref:
    zip_ref.extractall(extract_path)

print("Giải nén xong.")
