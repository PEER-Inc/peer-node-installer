<h2>RUN THE NODE (IN DEV MODE)</h2>
<b>sudo ./peer --dev --tmp</b>
<br>
(By executing the above command we are running the network in development mode with a single validator)
<br>

<h2>BUILD</h2>
The codebase comes with an in-built binary which can be executed directly with the below command.
<br>
<br>

<b>RUN THE BELOW COMMAND TO CONNECT TO MAIN NETWORK</b>
<br>

sudo ./peer   --base-path /data/PeerDemo   --chain ./customSpecRaw.json   --port 30333   --ws-external   --rpc-external --rpc-cors all  --no-telemetry --validator   --rpc-methods Unsafe --name PeerDemo   --bootnodes /ip4/52.9.46.195/tcp/30333/p2p/12D3KooWLh7brV2vkqbGm3P2PiCd7Kc1aQxJ2187U64CBhgt4gc1

<h2>CODE TEMPLATE STRUCTURE</h2>
<b><h3>The template consists of 2 files</h3></b>
<b><i>1.peer</i></b>
<br>
<br>
   The binary is provided to users without needing to build the code again, Using this they can run a node directly.After rsuccesfully running the node the user has become part of the blockchain        network.
   <br>
   <br>
<b><i>2.customSpecRaw.json</i></b>
<br>
<br>
   A chain specification is a source code file that defines a Substrate chain's initial (genesis) state. 

