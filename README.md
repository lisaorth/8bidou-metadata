# 8bidou-metadata
Simple metadata template to add to your 8didou piece when minting.

First get a free pinata account to pin your image and metadata, sign up here:

https://www.pinata.cloud/

Upload your PNG image file to Pinata. You'll get its CID location, which will be an alphanumeric string that starts with Qm
As an example, the CID for my first PNG file was: QmPrd3H8MDhmHkj8Uy4cTcZ5SXccHMtwzt7A64E8XFmMR1

You can confirm that your file is uploaded and displaying correctly by copying the CID number to the end of this address:

https://ipfs.io/ipfs/

Example: https://ipfs.io/ipfs/QmPrd3H8MDhmHkj8Uy4cTcZ5SXccHMtwzt7A64E8XFmMR1

You might need to view it in an incognito window or in a browser that doesn't have the ipfs extension, so keep that in mind if it's not showing up at first

After you confirm your PNG file is correctly pinned and displaying properly you can make your metadata.json file

Copy the code from "template_metadate.json" and paste into your editor. If you don't have an editor you can check out free text editors at:

https://www.sublimetext.com/
or
https://code.visualstudio.com/

You'll want to replace the following with your own information:

name: This will be the title of your piece
description: Description of your piece

You'll need to replace ALL of the lines below with the same CID (alphanumeric string that starts with Qm) that was assigned to your PNG

"image":"ipfs://Qm-YOUR-CID-HERE", 
"artifactUri":"ipfs://Qm-YOUR-CID-HERE", 
"displayUri":"ipfs://Qm-YOUR-CID-HERE", 
"thumbnailUri":"ipfs://Qm-YOUR-CID-HERE", 
"formats":[{"uri":"ipfs://Qm-YOUR-CID-HERE",

(Don't add anything to the above code after ipfs:// besides your QM)

Replace "tzYOUR-TEZOS-WALLET-ADDRESS-HERE" with your Tezos wallet address (your address starts with tz)

"creators":["tzYOUR-TEZOS-WALLET-ADDRESS-HERE"],

Leave all other infornation the same!

You can name your file whatever you want as long as it ends with .json
An example: my-project-name-metadata.json

Upload your metadata.json file to Pinata, and get the CID (alphanumeric string that starts with Qm)

For example, my metadata.json CID was: QmNe6nDVFAtURnewuy76X7rxdz4LSTweAkjMq4L2xgxq55

You can confirm that your metadata.json file is uploaded and displaying correctly by copying the CID number at the end of this address:

https://ipfs.io/ipfs/

Your link to your metadata.json file is what you will input into the metadata field when minting on 8bidou, instead of the localhost prepopulated info

Example: https://ipfs.io/ipfs/QmNe6nDVFAtURnewuy76X7rxdz4LSTweAkjMq4L2xgxq55 

If you need help uploading your PNG or metadata.json files please check out all the info here:

https://docs.pinata.cloud/
