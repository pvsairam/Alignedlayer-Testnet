![image](https://github.com/pvsairam/pvsairam-Alignedlayer-Testnet/assets/9134015/4fab5005-dc94-48e3-b6bf-96615e0dac2a)

> Aligned aims to accelerate Ethereum's roadmap by making proof verification faster and cheaper, reducing costs by up to 90%.
>
> Ethereum wasn't initially designed for ZK proofs, and integrating new primitives is challenging. Aligned Layer will transform Ethereum into an efficient, cost-effective platform for SNARK verification.
>
> They maintain neutrality, supporting all involved in zero-knowledge technology development and research, focused on expanding Ethereum's ZK capabilities to enable a future of trustless applications using verifiable computation and Ethereum's security.


# *Getting Started*

```bash
sudo apt update -y
sudo apt upgrade -y
```

## Install curl

```bash
sudo apt-get install curl -y
```

## Download AlignedProof

```bash
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
```
```bash
source /root/.bashrc
```

## Download SP1 proof

```bash
curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```

## Sending Proof

```bash
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```

## Use the explorer link in CMD to check if verified and you'll also see below image.

![image](https://github.com/pvsairam/pvsairam-Alignedlayer-Testnet/assets/9134015/35e80ed4-2f74-4f8d-bbd7-fce969a5676a)


![image](https://github.com/pvsairam/pvsairam-Alignedlayer-Testnet/assets/9134015/a79ea3b0-306d-4724-b695-f139a771cb21)


## Tweet exactly as screenshot and Submit Proof in Discord

![image](https://github.com/pvsairam/pvsairam-Alignedlayer-Testnet/assets/9134015/f4cd5eff-aea0-477c-9500-368a52d7d755)

https://x.com/xtestnet/status/1802972477964144643

## Submit in Discord

![image](https://github.com/pvsairam/pvsairam-Alignedlayer-Testnet/assets/9134015/9b6d7b0b-1dca-41d0-8d89-22ae181beb94)


## Valid Links:

https://linktr.ee/AlignedLayer

