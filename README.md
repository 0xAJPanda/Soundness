![Soundness Image](https://github.com/0xAJPanda/Soundness/blob/main/soundness.jpg)


# Soundness Testnet Registration (NO VPS REQUIRED)

**About Soundness Layer**  
Soundness Layer is a **decentralized verification layer** that aims to dramatically reduce **on-chain costs** for verifying Zero-Knowledge Proofs (ZKPs) while ensuring **fast finality** and **censorship resistance**. By leveraging **parallel execution** (Sui), **Move’s secure contracts**, and **Walrus’s decentralized storage**, Soundness Layer supports a wide range of use cases—from zk-Rollups to zkApps—without sacrificing performance or decentralization.

### Key Features
- **Fast Finality**: Proofs verified in seconds.  
- **Censorship Resistance**: No single entity can block or reorder transactions.  
- **Shared Economic Security**: Validators re-stake assets across multiple blockchains.  
- **Cross-Chain Interoperability**: Proofs efficiently verified across different networks using decentralized data availability.

<p align="center">
  <img src="https://raw.githubusercontent.com/0xAJPanda/Soundness/main/backed.jpg" alt="Backed Image" width="300" />
</p>


---

## Steps to Register for the Soundness Testnet

1. **Visit the Official Website**  
   [https://soundness.xyz/](https://soundness.xyz/)  
   Submit your email (try to use the same email as your GitHub account).

2. **Create a Repo on GitHub & Launch a Codespace**  
   [http://github.com/codespaces](http://github.com/codespaces)  
   Open a terminal in your Codespace and run the following commands:


```bash
sudo apt update && sudo apt upgrade -y
```

```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```

```bash
source /home/codespace/.bashrc
```

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```

```bash
. "$HOME/.cargo/env"
```

```bash
soundnessup install
```

```bash
soundnessup update
```

Generate your key and save it , DO NOT SHARE IT!

```bash
soundness-cli generate-key --name my-key
```

```bash
soundness-cli export-key --name my-key
```

### Join Discord
[https://discord.gg/ZrCbgE2q](https://discord.gg/ZrCbgE2q)  
Go to **#Testnet-access** and submit your **Pub-Key**.

The registration will reopen soon so get your pub-key ready, join the discord and wait for the annoucement. 

## Done!

### Additional Details
[https://x.com/SoundnessLabs/status/1902389758527152586](https://x.com/SoundnessLabs/status/1902389758527152586)
