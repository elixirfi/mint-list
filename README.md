# bs-mint-list
This is a repository for storing the valid NFTs to be deposited into different bridgesplit pools. Some pools are collection specific, some are across collections or specific to different parts of the metadata.

At some point, if we do this for a while it'll make sense to build this ourselves. But for now we can just use magic eden.

To add a new pool, add the fnft token mint as a new folder in the /pools directory and create a list.json file in the new directory.

To get these for a new collection, our current method is finding an NFT, copying it's verified creator, and then looking it up here: https://magiceden.io/mintlist-tool

<img width="1691" alt="image" src="https://user-images.githubusercontent.com/38018183/172682479-f928cec1-64dd-47ed-b255-56b64f6b0ac8.png">

Once you have the list of mints, copy them from the list generated and paste the array into the json file.
