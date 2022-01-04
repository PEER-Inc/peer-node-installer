<h3>RUN THE NODE (IN DEV MODE)</h3>
<b>sudo ./peer --dev --tmp</b>
</br>
(By executing the above command we are running the network in development mode with a single validator)
</br>

<h3>BUILD</h3>
The codebase comes with an in-built binary which can be executed directly with the below command.
</br>
<br>

<b>RUN THE BELOW COMMAND TO CONNECT TO MAIN NETWORK</b>
<br>

sudo ./peer   --base-path /data/PeerDemo   --chain ./customSpecRaw.json   --port 30333   --ws-external   --rpc-external --rpc-cors all  --no-telemetry --validator   --rpc-methods Unsafe --name PeerDemo   --bootnodes /ip4/52.9.46.195/tcp/30333/p2p/12D3KooWLh7brV2vkqbGm3P2PiCd7Kc1aQxJ2187U64CBhgt4gc1


</br>
<h3>CODE TEMPLATE STRUCTURE</h3>
<b>The template consists of 2 files</b></br>
1.NODE BINARY</br>
   The binary is provided to users without needing to build the code again, Using this they can run a node directly.After rsuccesfully running the node the user has become part of the blockchain        network.
   </br>
2.CHAIN SPEC</br>
   A chain specification is a source code file that defines a Substrate chain's initial (genesis) state. 

