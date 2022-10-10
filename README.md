#  Fintech Finder Crypto Payments

This challenge builds a cryptocurrency payment system using Ethereum blockchain network for a fictional Fintech Finder application. In this application customers can find a list of fintech professionals, then choose one to hire, and pay using Ethereum.

---

## Technologies

The stable version of this project can be run on Windows, Mac OS, or Linux as long as the user's 
environment has the following:
- python 3.7
- web3
- streamlit
- dataclasses
- typing
- bip44
- dotenv
- requests

---

## Installation Guide

You have a few options to install this application on your computer, two popular options are:

1. Download a ZIP of this repositories files 
[here](https://github.com/warp-9000/challenge-19-fintech-finder/archive/refs/heads/main.zip).

2. [Fork this respository](https://docs.github.com/en/get-started/quickstart/fork-a-repo "Fork a Repo - 
GitHub Docs") to your github account.

<p align="center">
<img src="https://github.com/warp-9000/uw-fintech-2022-module01-challenge/blob/main/instructions/github-fork-button-screenshot.png?raw=true" 
alt="Fork UI on GitHub.com"
width="55%"/>
</p>

After forking the respository you can use `git clone 
your-username@domain.com:your-git-username/challenge-19-fintech-finder.git` 
to download a copy of the forked respository to your computer.

Forking has the added benefit of enabling your to easily keep your copy of the 
application up-to-date should any changes or improvements be made in the future.

---

## Usage

***Please note:*** *these usage instructions assume you have setup an environment where
the python version, libraries, and frameworks listed in [Technologies](#Technologies) are installed.*

1. In the terminal, navigate to folder where you've downloaded this code.
2. Launch Ganache, and replace the MNEMONIC in the '.env' file with your version.
3. In the terminal, run application by using 'streamlit run fintech_finder.py'.
4. In the sidebar, choose a fintech professional to hire, set an amount of time, and click the **Send Transaction** button. Do this several times to store multiple transactions in the blockchain.

### Examples of the application running:

Before sending a transaction:
<p align="center">
<img src="https://raw.githubusercontent.com/warp-9000/challenge-19-fintech-finder/main/screenshots/Screen%20Shot%202022-10-09%20at%2010.30.21%20PM.png" 
alt="Fintech Finder Payment App" width="85%" />
</p>

After sending a transaction:
<p align="center">
<img src="https://raw.githubusercontent.com/warp-9000/challenge-19-fintech-finder/main/screenshots/Screen%20Shot%202022-10-09%20at%2010.30.42%20PM.png" 
alt="Fintech Finder Payment App" width="85%" />
</p>

The list of transactions in Ganache:
<p align="center">
<img src="https://raw.githubusercontent.com/warp-9000/challenge-19-fintech-finder/main/screenshots/Screen%20Shot%202022-10-09%20at%2010.31.38%20PM.png" 
alt="Fintech Finder Payment App" width="85%" />
</p>

The change in the account's Ether balance:
<p align="center">
<img src="https://raw.githubusercontent.com/warp-9000/challenge-19-fintech-finder/main/screenshots/Screen%20Shot%202022-10-09%20at%2010.32.46%20PM.png" 
alt="Fintech Finder Payment App" width="85%" />
</p>

---

## Contributors

Thanks!

<a href="https://github.com/warp-9000/challenge-19-fintech-finder/graphs/contributors">
<img src="https://contrib.rocks/image?repo=warp-9000/challenge-19-fintech-finder" />
</a>

<!-- 

---

## License

This project is licensed under ... Please see the LICENSE file 
[here](https://github.com/warp-9000/uw-fintech-2022/blob/main/Module-02/Challenge/loan_qualifier_app/LICENSE). 

-->
