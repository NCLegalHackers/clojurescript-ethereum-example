# Clojure Ethereum Example

## TriClojure Meetup Code


*This Code is a rewrite of the original code used as an example Clojurescript Ethereum App by Matus Lestan in the Medium post and repo below. This App is for Demonstration purposes and the original has been modified to use Boot, Hoplon and Hoplon AOM.



This is the source code for the original  tutorials:
 * [How to create decentralised apps with Clojurescript re-frame and Ethereum](https://medium.com/@matus.lestan/how-to-create-decentralised-apps-with-clojurescript-re-frame-and-ethereum-81de24d72ff5#.nvfyq27lb)
 * [How to deploy Clojurescript app into distributed storage IPFS](https://medium.com/@matus.lestan/how-to-deploy-clojurescript-app-into-distributed-storage-ipfs-e9d02cdfbc20#.ax3ra84bz)

Deployed at:
 * https://clojurescript-ethereum-example.herokuapp.com/
 * https://ipfs.io/ipns/QmXj5vKEKSU4kkjGnWq9ZJeG4xrkacDugme4iXz6qtvPgN/

## Start App
Start Solidity auto compiling
```
lein auto compile-solidity
```
Start less compiling
```
lein less4j auto
```
Start App
```
lein repl
```
```clojure
(clojurescript-ethereum-example.core/-main)
(figwheel-sidecar.repl-api/start-figwheel! (figwheel-sidecar.config/fetch-config))
(figwheel-sidecar.repl-api/cljs-repl)
```
Open at http://localhost:6655/

