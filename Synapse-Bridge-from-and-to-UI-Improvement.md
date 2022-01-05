# Synapse - Bridge from and to UI Improvement
Aim: tighten up [from] and [to] selection.  

Current:  
  - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fkydo-crypto%2F-1ClcYymDT.png?alt=media&token=f49d5026-bb5f-42dd-aed8-67ddf61f8c91)  
  - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fkydo-crypto%2F5vOwvPO1jz.png?alt=media&token=4d6e6aa3-4485-41b0-8c0d-3947b025bdcb)  

Pain point: takes a few scroll to find the chain I need. Unsure about the ordering of the chains.  
  - Similar from other projects:   
  - Sushi's UI is also confusing, I think showing the users a lot of choices is generally not great.  
    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fkydo-crypto%2FgoAchZwLiw.png?alt=media&token=2181fa60-5433-4e12-bbb6-c818973621db)  

Solution:  
  - Order by user count: based on the amount of users interacting with different chains. Reorder weekly.  
  - Order by volume: based on total volume on each chain from the bridge. Reorder weekly.  
  - Order by alphabet: based on the starting letter of the chains.  
  - Order by group: ETH + L2s. Other L1s.  
