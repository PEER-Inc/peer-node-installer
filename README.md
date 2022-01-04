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

sudo ./peer  \ </br> 
--base-path "path-to-store-db" \ </br> 
--chain ./customSpecRaw.json \ </br> 
--port 30333 \ </br> 
--ws-external \ </br> 
--rpc-external \ </br> 
--rpc-cors all  --no-telemetry  \ </br>
--validator   / </br> 
--rpc-methods Unsafe / </br>
--name "node-name"  / </br> 
--bootnodes /ip4/54.203.72.205/tcp/30333/p2p/12D3KooWENFuK8SzBoPkfmiVnaSB8wWbMhknxcNeBiCU98DJoXhU 


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
