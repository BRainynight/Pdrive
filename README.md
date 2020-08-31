# 原始模組
- 從[PyDrive](https://gist.github.com/Joshua1989/dc7e60aa487430ea704a8cb3f2c5d6a6#file-colab_util-py) 修正
下載原始的包:
  ```
  pip install -U -q PyDrive
  ```

# 修正
- 主要是 `GoogleDriveHandler.upload` 方法的修改，可能因為版本的更新，在再度上傳同名檔案時，原始的模組沒辦法真正的刪除舊的檔案，因此做了一些修正。
- 在目前的版本中，這個方法似乎會跳警告，但是不影響運作。
