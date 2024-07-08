# ALIGNEDLAYER PUBLIC PROOF TASK  

![image](https://github.com/kotipichla/alignedlayer_testnet_proof_submission/assets/152254884/40028b04-deb9-47a5-8176-ffa6aef8f02b)


## Getting Srtarted 

```
sudo apt update -y
sudo apt upgrade -y
```

### Install curl 
```
sudo apt-get install curl -y
```

### Download ALignedProof 
![image](https://github.com/kotipichla/alignedlayer_testnet_proof_submission/assets/152254884/fd46e154-29cf-465a-af4a-d481650d3e21)

```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
```

```
source /root/.bashrc
```


### Download an example SP1 proof file with it's ELF file 
![image](https://github.com/kotipichla/alignedlayer_testnet_proof_submission/assets/152254884/a325bf44-096e-43db-b1c0-5eea668cf155)


```
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```


### Sending proof 

![image](https://github.com/kotipichla/alignedlayer_testnet_proof_submission/assets/152254884/52642b86-2e8b-493e-b9eb-2c87558495f0)

```
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```

use this code to get the log you will screenshot for your X post
```
aligned verify-proof-onchain \
--aligned-verification-data ~/aligned_verification_data/*.json \
--rpc https://ethereum-holesky-rpc.publicnode.com \
--chain holesky
```


Use the explorer link in CMD to check if verified and you'll also see below image. 
![image](https://github.com/kotipichla/alignedlayer_testnet_proof_submission/assets/152254884/3b7a1c6f-9f0b-41ce-8da8-10e6be295f7b)

![image](https://github.com/kotipichla/alignedlayer_testnet_proof_submission/assets/152254884/eeaf9379-f727-4aa5-ac46-7ac88b7751d5)



-------------
----------------------
### Tweet exactly as screenshot and Submit Proof in Dscord 

![image](https://github.com/kotipichla/alignedlayer_testnet_proof_submission/assets/152254884/6afdae2b-ba45-4664-a3f3-1f87bdcd5fa8)



--------------------------
### Submit in Discord 
![image](https://github.com/kotipichla/alignedlayer_testnet_proof_submission/assets/152254884/071a8ce4-cdc3-4e41-ae22-6386053ac90c)


# JOIN DISCORD FROM PROFILE 
https://linktr.ee/AlignedLayer




