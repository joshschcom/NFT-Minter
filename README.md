# Commands for the Terminal

`npx create-react-app SAMPLENAME

npm run start

CONTROL+C to stop web3 app

npm i web3

npm i ethers

npm i react-bootstrap bootstrap@5.1.3

npm i axios`

# What we added / deleted
We have used hashlips to generate the NFTs & metadata BUT we should have uploaded them all at once via f.e. pinata so that we can show them on our frontend, because we didnt do that the main page only shows one specific picture.

Line 751 Add behind nftpng: + result.tokenID +`.png`

We removed: <div className="ml-3 mr-3" style={{ display: "inline-grid", gridTemplateColumns: "repeat(4, 5fr)", columnGap: "10px", }} >

On Line 746 Because our NFT is too big and we dont want a sideways grid. Dont forget to add </div>

Original made by n2d
