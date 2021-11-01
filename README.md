# How To Upload DataSet In Kaggle

## Important commands------------------------------------------------

### Initialize the Dataset Folder---------
```bash
kaggle datasets init -p \Desktop\CT-Kidney
```

### activating env
```bash
conda activate ./env

```
### Upload data/Folder/No need to Zip the folder
```bash
 kaggle datasets create -p <Path> --dir-mode zip
 
 kaggle datasets create -p Desktop\CT-Kidney --dir-mode zip
 ```
 
 ## Update - Underscore in title throws error.
 ## Slug is normally the title name (small letter) and instead of space we should use - and no special letter should use.
 
 
 ## Reference:
 * [Uploading & Updating Datasets with the Kaggle API](https://kiosk-dot-codelabs-site.appspot.com/codelabs/upload-update-data-kaggle-api/index.html?index=..%2F..index#1)
 * [Kaggle API, New Version of Data](https://www.kaggle.com/docs/api)
 * [Kaggle API Github](https://github.com/Kaggle/kaggle-api)
 * [Upload folder](https://www.kaggle.com/general/190002)
 * [MetaData/SlugDocumentation](https://github.com/Kaggle/kaggle-api/wiki/Dataset-Metadata)




