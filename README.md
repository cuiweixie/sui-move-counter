# cmds
```
./sui/target/debug/sui move new counter 
../sui/target/debug/sui move build
../sui/target/debug/sui move build
../sui/target/debug/sui client publish 
../sui/target/debug/sui client faucet 
../sui/target/debug/sui client publish 
../sui/target/debug/sui client call --package 0xf95479a0d8feb8061e97fbe4bfb4690c21e3333a4ed1296699aa55f81d157571  --module counter --function create
../sui/target/debug/sui client call --package 0xf95479a0d8feb8061e97fbe4bfb4690c21e3333a4ed1296699aa55f81d157571  --module counter --function increment --args 0x1e8f827f7afa1e478c025dc1900b6757bd194352c1173b3fb3218a780da69f94
# 0xa40203f8291cb09185e7732c31b948e3f45458794e555f9248947edc732dca1e
../sui/target/debug/sui client call --package 0xa40203f8291cb09185e7732c31b948e3f45458794e555f9248947edc732dca1e  --module counter --function create_and_transfer_counter --args 0xa40203f8291cb09185e7732c31b948e3f45458794e555f9248947edc732dca1e


```
