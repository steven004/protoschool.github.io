Fill in the body of the `traversePosts()` function. It takes the CID object of the most recent blog post as input. Use that to get the object from IPFS and follow the `prev` links. The return value of the function should be an array with the CID objects of all nodes (including the input CID).