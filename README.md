# Advanced_programming
## Scenario
Imagine TripAdvisor. Is there any functionality which would improve this gigant in the trip applications? Well, ask yourself: "How are you motivated to recommend some place to stay, eat or to do something interesting?" Yes, beside that you want to share just your experiences from your own will, you can now even earn some money by doing so and that is amazing, don't you think? Plus, it is decentralized, meaning no one can pay money to remove their negative reviews.

Link to the ReviewDAO presentation including more detailed description: https://showcase.ethglobal.com/daohacks/reviewdao-qp5ih

Project github: https://github.com/smrza/ReviewDAO


## Requirements
1. Anybody can join the DAO community by acquiring an NFT or fungible tokens. NFT for list governance, fungible token for listings governance.
2. NFT holders propose new list 
3. Vote for proposed lists
5. There is only one winner of the proposed list within each period 
6. Subjects with enough native fungible tokens can apply for listing at their chosen list
7. Challenge subjects
8. UpVote the challenged item
9. DownVote the challenged item

## Used Technologies
- Solidity
- Ethereum blokchain
- Graph https://thegraph.com/en/
- React
- (AWS s3, DynamoDB)

## Questions
- Is blockchain safe?
  - Of course. It is decentralized and promoting transparency and community engagement. 
- How many lists can be there?
  - infinite, since we are utilizing the power of the blockchain and lists have their own contracts
- How many listings can be there?
  - infinite, lists have their own contracts and as many subjects as uint256

## Time plan
##### Jan Smrza
![timeline](https://user-images.githubusercontent.com/69464039/167244203-f2329d81-6424-4ce2-8ede-f3cef84227a7.png)
   
* commit 1	https://github.com/smrza/ReviewDAO/commit/3aa9a56e8f916d24410c2ee6ac31e85950711af4
* commit 2	https://github.com/smrza/ReviewDAO/commit/8c6d21aedaa0ea2f20304df505a0444be1271a00
* commit 3	https://github.com/smrza/ReviewDAO/commit/b2ddcea3a9e1e7e7b23b41c5e93acf2e365f3896
* commit 4	https://github.com/smrza/ReviewDAO/commit/4495bb3f42115caa0869a7e96a78263b9c4eea9e
* commit 5	https://github.com/smrza/ReviewDAO/commit/ead056ce6a3f5b99d3ddc8902885c2d75c71960b
* commit 6	https://github.com/smrza/ReviewDAO/commit/36c1df0292ab46107eeaf086bd55d9b2263e4984
* commit 7	https://github.com/smrza/ReviewDAO/commit/3719387cba12796608086add63e2759fd01cb256
* commit 8	https://github.com/smrza/ReviewDAO/commit/9bd9bd4d9bbd9f601bdffe9e457714b980c6a46f
* commit 9	https://github.com/smrza/ReviewDAO/commit/e9d4280cc537bf3ccdfa1f1490ec10d9a47486c3
* commit 10	https://github.com/smrza/ReviewDAO/commit/407a19337652061a0181ac28cd09116360e200fb
* commit 11	https://github.com/smrza/ReviewDAO/commit/e646d671ea6cdc29f2bf69b8f317fa183423dcd8
* project showcase	https://showcase.ethglobal.com/daohacks/reviewdao-qp5ih


##### Jan Bures

| **Task**                                | **Spend time** | **Commit**                                                                         |
|-----------------------------------------|----------------|------------------------------------------------------------------------------------|
| Team discussion and planning            | 7              |                                                                                    |
| Technology research                     | 4              |                                                                                    |
| FrontEnd planning - routing             | 1              |                                                                                    |
| FrontEnd base                           | 6              |                                                                                    |
| Cards with static data                  | 13             |                                                                                    |
| Metamask                                | 3              | https://github.com/smrza/ReviewDAO/commit/3f10795737896e548bef6f9ad2f86a25522a8ad9 |
| Forms with Formik                       | 5              | https://github.com/smrza/ReviewDAO/commit/369db1e16c58395c300e8943b28135950340c16c |
| IPFS - creation and displaying in cards | 6              | https://github.com/smrza/ReviewDAO/commit/45cfcd8cf63f09c132a1bf3774301537ceb9d0ae |
| Add Graph                               | 5              | https://github.com/smrza/ReviewDAO/commit/811d51feb995423c9fd40361353fed9e09033042 |
| Add contract                            | 3              | https://github.com/smrza/ReviewDAO/commit/aa7974c5997fc0b4613d75147635b645f6c13029 |
| Recomposing to the dynamic flow         | 15             | https://github.com/smrza/ReviewDAO/commit/c1ccb9aca69d037b5925d449e30814e94451af86 |
| Styling                                 | 5              |                                                                                    |


##### David Rábel

| **Task**                                | **Spend time** | **Commit**                                                                         |
|-----------------------------------------|----------------|------------------------------------------------------------------------------------|
| Team discussion and planning            | 7              |                                                                                    |
| Technology research                     | 20             |                                                                                    |
| TheGraph-Basics                         | 10             | https://github.com/smrza/ReviewDAO/commit/db236244035474594bc44c3b1d795df0efbd6fd2 |
| TheGraph-FirstContract connection       | 6              | https://github.com/smrza/ReviewDAO/commit/882b6d5bbe42ce8c297eb8073e0b00d22e051601 |
| TheGraph-SecondContract connection      | 10             | https://github.com/smrza/ReviewDAO/commit/86f625fca8ec9ff51bff8a4a24161f9624552bc6 |
| TheGraph-EndPoint                       | 3              |                                                                                    |
| TheGraph - Reworking to Factory         | 12             | https://github.com/smrza/ReviewDAO/commit/1f6d7a0ca162d991a710d7b0b5ca62d391036987 |
| TheGraph - Testing                      | 2              |                                                                                    |
| TheGraph - Connection to FR             | 5              | https://github.com/smrza/ReviewDAO/commit/c1ccb9aca69d037b5925d449e30814e94451af86 |         
