# Build a Decentralized Voting Dapp with Next.js, TypeScript, Tailwind CSS, and CometChat

1. Create a CometChat project, copy and paste your key in the spaces below.
2. Update the `.env` file with the following details.
   ```sh
    NEXT_PUBLIC_COMET_CHAT_APP_ID=<CometChat_APP_ID>
    NEXT_PUBLIC_COMET_CHAT_AUTH_KEY=<Comet_Chat_AUTH_KEY>
    NEXT_PUBLIC_COMET_CHAT_REGION=<CometChat_REGION>
    NEXT_APP_RPC_URL=<http://127.0.0.1:8545>
   ```
3. Run the app using the following commands.
   ```sh
   yarn install
   yarn hardhat node
   yarn hardhat run scripts/deploy.js
   ```
4. On another terminal, run `yarn start` to launch the project on the browser.
5. Add some hardhat accounts, connect your wallet and interact with the app.
   <br/>
