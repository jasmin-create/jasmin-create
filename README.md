const NFTs = []

function etsatinsaj (_name, _boygroup, _girlgroup, _mysong, _boybias, _girlbias) {
    const NFT = {
        "NAME": _name, 
        "BOY GROUP": _boygroup,  
        "GIRL GROUP": _girlgroup, 
        "MY SONG": _mysong,
        "BOY BIAS": _boybias,  
        "GIRL BIAS": _girlbias 

    
    }
    NFTs.push(NFT); 
    console.log("etsatinsaj: " + _name)  
}

function listNFTs () {
for(let i = 0; i  < NFTs.length; i++) {
console.log(NFTs[i])
}
}

function getTotalSupply() {
console.log(NFTs.length); 
}


etsatinsaj("Jasmiin", "Enhypen","New Jeans", "OMG", "Jay", "Danielle")
listNFTs(); 
getTotalSupply();
