# STARKNET交互宝典

1. argentx和braavos钱包的开户脚本和奥德赛学习脚本，随任务不定期更新，如果您在学习中遇到问题，可以在我推特留言或DM https://twitter.com/buxiaozhizi
2. 脚本引用的第三方包，大家可以自行去下载，安全方面自己要把最后一关，WEB3黑暗森林生存法则：不要轻信任何人

之前把这个仓库的代码定位成撸毛的想法是错误和肤浅的，更正一下，本仓库代码是为了建立更加美好的starknet生态而生，通过starknet交互代码给小白和想进入web3世界的新人提供更多接触优质平台的参考资料。
    
因为没有太多精力，因此近期暂不考虑使用其他语言，不喜欢用js的朋友请见谅

最后更新 2023.07.28
---
spok的claim学习脚本，代码复刻了八周任务的脚本，仅修改了合约地址和领取id而已。

1. 批量钱包的地址和私钥需要放置在argent/wallets.json文件中，格式参考文件中说明

需要用到的三方包：
1. ethers https://www.npmjs.com/package/ethers/v/5.7.2
2. starknet.js https://www.starknetjs.com/docs/API/
3. request https://www.npmjs.com/package/request 虽然过时不维护了，但我用顺手了，而且不更新的反倒觉得很安全

免责声明
---
本项目的代码仅供学习和研究目的，不得用于任何非法用途。使用本代码产生的任何后果与作者无关。在使用本项目的代码时，请遵守当地法律法规。
1. 仅供学习和研究
本项目的代码旨在帮助用户了解相关技术和知识，以促进技术交流和发展。请在遵守法律法规的前提下，合理使用本项目的代码。
2. 禁止非法用途
严禁将本项目的代码用于任何非法用途，包括但不限于侵犯他人权益、违反法律法规等行为。如有违反，后果自负。
3. 遵守法律法规
在使用本项目的代码时，请确保遵守当地法律法规。如有疑问，请咨询专业律师。
4. 免责
作者不对使用本项目的代码产生的任何后果承担法律责任。用户在使用本项目的代码时，应自行承担相应的法律风险。
在使用本项目的代码时，您已明确了解并同意本免责声明。如您不同意本声明，请立即停止使用本项目的代码。
