# youtube-emotion-mining

conda create -n youtube_sentiment python=3.11 -y

conda activate youtube_sentiment

pip install -r requirements.txt


## DVC

dvc init

dvc repro

dvc dag



## AWS

aws configure



### Json data demo in postman

http://localhost:5000/predict

```python
{
    "comments": ["This video is awsome! I loved a lot", "Very bad explanation. poor video"]
}
```



chrome://extensions