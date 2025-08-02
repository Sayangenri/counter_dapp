# counter\_dapp

A full-stack starter project built using **AlgoKit** to help you develop decentralized applications on **Algorand** using **Python** and **React**.


## Video Walkthrough

🔝 [Watch on YouTube](https://youtu.be/-iRCX6m3SbY)


## 🚀 Setup Instructions

### Initial Setup

 **Clone the Repository**

   ```bash
   git clone <your-repo-link>
   cd counter_dapp
   ```

**Install Docker**
   Make sure Docker is installed and running:
   🔝 [Download Docker](https://www.docker.com/)

**Install AlgoKit**
   Follow the official guide to install AlgoKit:
   🔝 [Install AlgoKit](https://github.com/algorandfoundation/algokit-cli#install)

**Bootstrap the Project**

   ```bash
   algokit project bootstrap all
   ```

**Set Up LocalNet for Smart Contracts**

   ```bash
   cd projects/counter_dapp-contracts
   algokit generate env-file -a target_network localnet
   ```

**Build the Project**

   ```bash
   algokit project run build
   ```

**Notion Link for windows os** https://www.notion.so/AlgoKit-Full-Setup-on-Windows-with-WSL-241fe3ff0a208039a2bae351fd11d0b5


## 🛠️ Tools Used

### ⚙️ Backend / Smart Contracts

* **Python**
* **TypeScript**
* **AlgoKit** & **AlgoKit Utils**

### 💻 Frontend

* **React**
* **Tailwind CSS**

## 🔗 Quick Link

* **Smart Contracts:**
  [`projects/counter_dapp-contracts`](projects/counter_dapp-contracts/README.md)

* **Frontend App:**
  [`projects/counter_dapp-frontend`](projects/counter_dapp-frontend/README.md)


