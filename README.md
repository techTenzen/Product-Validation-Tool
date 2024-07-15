Live at ```https://validate1.onrender.com```
**Product Validation Tool** 🛡️

**Abstract** 🚀

Guarding consumers against counterfeit products is crucial. This project, built using Truffle, Ganache, and blockchain technology, offers a robust solution to verify product authenticity. Utilizing smart contracts and decentralized technology, it ensures that genuine products are easily distinguishable from fake ones.

**Setup Process** 🛠️

1. **Clone the Project** 📦
   ```bash
   git clone https://github.com/A4ANK/Fake-Product-Identification.git
   ```

2. **Install Required Packages** 📦
   Open your terminal, navigate to the project folder, and run:
   ```bash
   npm install
   ```

3. **Compile Contract Source Files** ⚙️
   Compile the smart contract source files using Truffle:
   ```bash
   truffle compile
   ```

4. **Setup Local Blockchain** ⛓️
   - Open Ganache and create a new workspace.
   - Add `truffle-config.js` from your project to the workspace.
   - Change the port in server settings to 8545 (same as port in `truffle-config.js`).

5. **Configure MetaMask** 🦊
   - In your Chromium-based browser (e.g., Chrome), open MetaMask.
   - Add a new test network with these settings:
     - NETWORK ID: 5777 (from Ganache Server settings)
     - RPC SERVER: HTTP://127.0.0.1:8545 (from Ganache Server settings)
     - CHAIN CODE: 1337

6. **Import Accounts from Ganache** 💼
   - Get a private key from any account available in Ganache's local blockchain.
   - Import this account into MetaMask.

7. **Migrate Contracts** 🚀
   In your terminal, run the following commands:
   ```bash
   truffle migrate
   ```

8. **Start the Server** 🌐
   Run the server to open the homepage (index.html) in your default browser:
   ```bash
   npm run dev
   ```

9. **Connect to Local Blockchain** 🔗
   - Log in to MetaMask and connect the added account to the local blockchain (i.e., localhost:3000).

10. **Interact with the Website** 💻
   Explore the website and leverage the power of blockchain to identify fake products effectively.

**Questions or Need Assistance?** 🤔

Feel free to reach out to us via email at **p.rajeshkumar2603@gmail.com** for any questions, inquiries, or assistance related to the Product Validation Tool project. We're here to help! 📧

**Screenshots** 📸

- ![Website Home Page](https://github.com/scattershott/Product-Validation-Tool/assets/147977105/4bb6e634-b166-4217-b957-6e217b15f4b1)
- [Adding Product](https://github.com/scattershott/Product-Validation-Tool/assets/147977105/aee35f70-b3eb-4e50-b01a-2cdcbe51186b)
- ![Generated QR Code](https://github.com/scattershott/Product-Validation-Tool/assets/147977105/6d7b0cc7-007a-4600-95a1-a7fb7f72e894)
- ![Product Verification](https://github.com/scattershott/Product-Validation-Tool/assets/147977105/0ec60b43-31dd-43ed-801a-aae34896632b)
- ![Ganache](https://github.com/scattershott/Product-Validation-Tool/assets/147977105/c8399a26-8b5e-4b3d-a6e6-c959831db17d)
- ![MetaMask](https://github.com/scattershott/Product-Validation-Tool/assets/147977105/b42202f2-af62-48ce-aeeb-4b939d98203e)

👉 This enhanced setup process provides clarity and engagement for users looking to set up and use your Fake Product Identification project.

**Interact with the Website 💻**

Congratulations! You're all set to explore the world of product authenticity verification. With your local blockchain, MetaMask, and our blockchain-powered solution, you're well-equipped to distinguish genuine products from counterfeits. Simply connect your MetaMask account, and dive into a safer and more secure consumer experience. Enjoy your journey in the quest for authenticity and trust.

Feel free to reach out if you have questions, suggestions, or want to share your experience. We're here to help! 📧

Now, go ahead and explore the website to see how it can safeguard consumers against counterfeit products.
