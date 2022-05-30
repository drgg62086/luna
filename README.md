
# [Proposal] - launch multi-person online collaborative painting activities(like reddit's r/place) regularly and Generate NFT automatically using the result of each activities

(Introduction about "r/place" : https://en.wikipedia.org/wiki/R/place)

this activity may require the development of some DAPP,
or just need to create two smart contract:  
1.user send a little luna to this address to modify some pixel color  
2.Generate NFT regularly and auction automatically  

and the auction proceeds (including the bonus on every trade after that) should be used partly buy luna for burning and partly is allocated to participants,
that will also encourages people to get involved and speed up the burning 

------------------------------------------------------------------------------------------------------------------------------------------

## note1:

There are several interesting places to adjust.   
For example, there are at least two modes can be set:    
'normal mode' or 'auction mode'  

in 'normal mode',the transaction sent after will overwrite the previous one
It's will be the same as common pixelplace game like "r/place"

but in 'Auction mode' , if someone want to modify a pixel that has been modified by others, they need to send more amount than others  

and Then, in the step of generation of NFT, some restrictions can be added in to it.   
For example, the number of participants needs to exceed a certain amount, and the casting can be successful only when the drawing results meet specific conditions (It's like calculating hash when bitcoin mining)  

and the final allocation process can be also added some conditions, 
for example , the last modifier to each pixel on the canvas will get more bonus


## note2:

**The casting process of NFT is automatic, and the nft generated in this way does not belong to anyone in the first place,
it also be different from the usual way of generate NFT in the past**

## note3(2022-5-17):

Using blockchain to realize 'r/place' activities will make NFT not need image file ,Because previous transaction is already contains all the RBG data  

## note4(2022-5-18):
in fact, the fungible token was also be mint by collaboration mode(bitcoin mining)  
why can't Non-Fungible Token be created in multiplayer collaboration mode?

## note4(2022-5-29):
I thought a new model about the overwrite rule of place pixel: 
add a random string to the 'memo' and concatenate some summary info in transaction(for example:'block height','sender and receiver address','amount','memo') to a string  
and calculate the hash of this string(use SHA-256)
the smaller result will overwrite others

------------------------------------------------------------------------------------------------------------------------------------------


 If you think this is a good ideal, please retweet it or start a crowdfunding campaign on Gitcoin, and I’m willing to pay a little money for it.  
 Or if you have a better idea, please send a email to me :  drgg62086@gmail.com

------------------------------------------------------------------------------------------------------------------------------------------


(_The above content was translated with a translation tool, I don't know English very well, there may be some problems with the translation, but the general meaning should be correct_)
