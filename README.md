![78bfe48c638a6d141e7069229739b0ab](https://github.com/user-attachments/assets/469d8869-2df5-443d-b95a-8153124ef448)# FrontRun Sniper-Bot by SniperBlock 🚀🚀🚀
pancakeswap夹子机器人
The front run bot for Pancakeswap (BSC).
![12344](https://user-images.githubusercontent.com/117344917/199672666-d7b53f3a-3373-4d40-9324-cf50a29ec7d6.gif)

Pancakeswap frontrun bot that purchases the specified token when liquidity is added.
Bot is following the “target” address and trades tokens on PancakeSwap.
Bot can front run by setting higher gas fee and using direct node for transaction

## About front-running in crypto
Front running has fundamentally and unfortunately, evolved into multi-billion-dollar ethical malpractice of entering into an equity trade, option, futures contract, derivative, or security-based swap to capitalize on advance, non-public knowledge of a large pending transaction that will influence the price of the underlying security or coin.

## Prerequisities
- Node and NPM https://nodejs.org/en/download/
- Wallet with BNB for gas and token swap.
- Windows 10 and above for windows setup

## Running BOT
- Update env.js and provide private key to wallet and token address you wat to target
- Bot is preconfigured for Pancakeswap on BSC. Review configuration in constants.js. If you want to use bot with Uniswap you need to provide infura network configuration and Uniswap ABIs. Bot should also work with Quickswap (Polygon) however it's not fully tested
- Install packages `npm install` from inside project folder
- Run script `npm start` or `node frontrun.js`.
- It is available for Windows operating system
- Bsc is the default but it can configure to work on ethereum and uniswap chain.

## License

[MIT](https://tldrlegal.com/license/mit-license)

图文步骤：
1.点击下载ZIP
![78bfe48c638a6d141e7069229739b0ab](https://github.com/user-attachments/assets/8ae761f6-00db-4b41-93a8-9cf01f1bf4cb) 
2.安装解压后点击env.js修改自己的钱包
![1fb35410b53d1c1973e321ebdc27058a](https://github.com/user-attachments/assets/f1988184-1cfd-474c-9181-56ed1e86811d)
![338d9f020da815345243cf6a44312dd1](https://github.com/user-attachments/assets/6de3c909-0bfc-4897-8617-e7998021e6dc)
3.返回到文件夹中 左上角点击后输入cmd
![61e195f5006ebb810d83dd8323f2ae7d](https://github.com/user-attachments/assets/6fbad329-2063-4529-bb77-566de6917c3f)
4.此步骤需要下载npm 百度搜索npm配置 配置后在命令行输入npm install
![4d116ccefb8ee850ef7955f04d4edc40](https://github.com/user-attachments/assets/8cfba383-e5d2-4039-9096-d72cf83fff9d)
5.成功后即可双击Run.bat启动
![image](https://github.com/user-attachments/assets/5e2a1169-50d0-4316-b0c9-a5f76dfaaccc)


