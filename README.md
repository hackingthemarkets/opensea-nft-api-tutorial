# opensea-nft-api-tutorial
OpenSea NFT API App using Python and Streamlit

## Tutorial Video Walkthrough

https://www.youtube.com/watch?v=49SupvcFC1M

## Instructions for Running
```
pip3 install -r requirements.txt
streamlit run nft.py
```

## cli.py and assets.json

This is a flat file of all assets in a collection. Since OpenSea NFT only lets you fetch 50 assets at a time, you can run cli.py to fetch all assets page by page and output the final data structure into a file called assets.json. The nft.py webapp reads in this data and performs the trait and rarity sort. 
