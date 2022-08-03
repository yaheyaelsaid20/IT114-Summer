<table><tr><td> <em>Assignment: </em> It114 Milestone1</td></tr>
<tr><td> <em>Student: </em> Yaheya Elsaid(yre2)</td></tr>
<tr><td> <em>Generated: </em> 8/3/2022 1:06:18 AM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-450-M22/it114-milestone1/grade/yre2" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch called Milestone1</li><li>At the root of your repository create a folder called Project</li><li>Create a milestone1.md file inside the project folder</li><li>Git add/commit/push it to Github</li><li>Create a pull request from Milestone1 to main (don't complete/merge it yet)</li><li>Copy in the latest Socket sample code from the most recent Socket Part example</li><ol><li>Recommended Part 5, but Part 4 should be sufficient</li></ol><li>Git add/commit the baseline</li><li>Ensure the sample is working and fill in the below deliverables</li><li>Get the markdown content or the file and paste it into the milestone1.md file or replace the file with the downloaded version</li><li>Git add/commit/push all changes</li><li>Complete the pull request merge from step 5</li><li>Locally checkout main</li><li>git pull origin main</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Startup </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot showing your server being started and running</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182319456-fda60c74-8433-468b-9fd8-32b612ed997a.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Server started and listening on port 300<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot showing your client being started and running</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182319696-50c4b401-e80d-44ee-8fe5-a84aa90f30fe.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Client started and running, waiting for input.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain the connection process</td></tr>
<tr><td> <em>Response:</em> <p>This connection is established by TCP, transmission control protocol. It specifically runs on<br>port 3000, a computer-interpreted port that establishes a connection between a local file<br>and to a file. Using java socket you establish a connection by connecting<br>the user IP address and port number to the servers, once the server<br>is running the computer loads the processed commands on local byte machine code<br>that can be interpreted, and therefore the server and client can communicate.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Sending/Receiving </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot(s) showing evidence related to the checklist on the right</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182524307-42581d92-d0ff-4b8a-b64f-146b15fff975.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>First client connected<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182524307-42581d92-d0ff-4b8a-b64f-146b15fff975.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Second clinet connected<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182525154-2a4bc525-a5be-4c10-97d5-8fa9cef80600.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Chatting<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain how the messages are sent, broadcasted, and received</td></tr>
<tr><td> <em>Response:</em> <p>First a client needs to connected to server to input messages, this is<br>implemented by isConnected method. Using localhost: 3000 you create a server socket the<br>allows connection between the server and the client. IsConnected makes sure the connection<br>is sent and the status is good, and there you can set the<br>name and type /connect to connect the client to server.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Disconnecting / Terminating </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot(s) showing evidence related to the checklist on the right</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182525233-a2b0cb8a-5e91-4098-9865-17d3a3cf9cf8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Successfully disconnection of the client while the server is running.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182525306-e83a46a3-9328-4af7-a5f8-e27db763315c.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Successfully disconnection of the server while the client is running.<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain how the various disconnects/terminations are handled</td></tr>
<tr><td> <em>Response:</em> <p>The termination is handled by the the printstacktrace, gives user friendly message that<br>the client is disconnected, that&#39;s when a disconnect keyword is applied. Also the<br>sets the status as message &quot;disconnect&quot;.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add the pull request for this branch</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/yaheyaelsaid20/IT114-Summer/pull/5">https://github.com/yaheyaelsaid20/IT114-Summer/pull/5</a> </td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-450-M22/it114-milestone1/grade/yre2" target="_blank">Grading</a></td></tr></table>