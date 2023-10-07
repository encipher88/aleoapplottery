# aleoapplottery

```
cd $HOME
sudo apt update && sudo apt upgrade -y
sudo apt install curl tar wget clang pkg-config git make libssl-dev libclang-dev libclang-12-dev -y
sudo apt install jq build-essential bsdmainutils ncdu gcc git-core chrony liblz4-tool -y
sudo apt install uidmap dbus-user-session protobuf-compiler unzip -y


cd $HOME
  sudo apt update
  sudo curl https://sh.rustup.rs -sSf | sh -s -- -y
  . $HOME/.cargo/env

git clone https://github.com/AleoHQ/leo
cd leo
cargo install --path .
mv /root/.cargo/bin/leo /usr/local/bin
which leo

leo account new
```
Private Key  ...
View Key  ...
Address  aleo12h7xppquv6dkmldalwkcpaxcjaahcvl9qcpg9d9hy2v05udz8vps39xd0y

```
leo example  lottery
```
Leo ✅ Created an Aleo program 'lottery' (in "/root/lottery")
Leo 🚀 To run the 'lottery' program follow the instructions at /root/lottery/README.md
```
cd /lottery
chmod +x "/root/lottery/run.sh"
"/root/lottery/run.sh"
```
       Leo ✅ Compiled 'main.leo' into Aleo instructions
⛓  Constraints
 •  'lottery.aleo/play' - 2,020 constraints (called 1 time)
➡️  Outputs
 • {
  owner: aleo1g2hf5almwaj78ntwppxdtk6urgqef532s2y5jmkg64mk9fqeu58qqflw94.private                                                                                                                  ,
  _nonce: 6827260855524558550681017951712560514574676528907595153477542599898331                                                                                                                  468175group.public
}
 • {
  program_id: lottery.aleo,
  function_name: play,
  arguments: []
}
       Leo ✅ Finished 'lottery.aleo/play' (in "/root/lottery/build")
 ```
 leo run play
```

       Leo ✅ Compiled 'main.leo' into Aleo instructions
⛓  Constraints
 •  'lottery.aleo/play' - 2,020 constraints (called 1 time)
➡️  Outputs
 • {
  owner: aleo1g2hf5almwaj78ntwppxdtk6urgqef532s2y5jmkg64mk9fqeu58qqflw94.private                                                                                                                  ,
  _nonce: 2881229315719604497618441691783147926686879040865483950554349378923718                                                                                                                  242183group.public
}
 • {
  program_id: lottery.aleo,
  function_name: play,
  arguments: []
}
       Leo ✅ Finished 'lottery.aleo/play' (in "/root/lottery/build")
