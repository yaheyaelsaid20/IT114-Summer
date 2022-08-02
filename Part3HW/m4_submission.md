<table><tr><td> <em>Assignment: </em> IT114 - Sockets Part 1 - 3</td></tr>
<tr><td> <em>Student: </em> Yaheya Elsaid(yre2)</td></tr>
<tr><td> <em>Generated: </em> 8/1/2022 10:16:51 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-450-M22/it114-sockets-part-1-3/grade/yre2" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch for this assignment</li><li>Go through the socket lessons and get each part implemented (parts 1-3)</li><li>Create a new folder called Part3HW</li><li>Create an empty m4_submission.md file in Part3HW</li><li>Add/commit/push the branch</li><li>Create a pull request to main and keep it open</li><li>Copy the the Part3 code into this new folder</li><li>Git add/commit all of the sample code and the Part3HW code</li><li>Implement two of the following server-side activities for all connected clients (majority of the logic should be processed server-side and broadcasted to all clients if/when applicable)</li><ol><li>Simple number guesser where all clients can attempt to guess</li><ol><li>Hint: may want separate commands to start, stop, and guess (or starting lasts for x rounds then stops)</li><li>No need to implement complexities like strikes</li></ol><li>Coin toss command (random heads or tails)</li><li>Dice roller given a command and text format of "roll #d#" (i.e., roll 2d6)</li><li>Math game (server outputs a basic equation, first person to guess it right gets congradulated and a new equatiion is given)</li><ol><li>Hint: may want a separate start, stop, answer commands (or starting lasts for x rounds then stops)</li></ol><li>Private message (a client can send a message targetting another client where only the two can see the messages)</li><li>Message shuffler (randomizes the order of the characters of the given message)</li></ol><li>Fill in the below deliverables</li><li>Save and generated the markdown or markdown file</li><li>Update the m4_submission.md file in the Part3HW folder</li><li>Add/commit/push your changes</li><li>Merge the pull request</li><li>From the M4-Sockets branch, navigate to your m4_submission.md file on github and copy the link</li><li>Submit the direct link to Canvas</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Baseline </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add as many screenshots as necessary to show basic communication among 3 clients and 1 server</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182276213-79591194-550b-4116-9792-d8a1dada00ef.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Flip a coin code<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Feature Implementation 1 </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> What feature did you pick? Briefly explain how you implemented it</td></tr>
<tr><td> <em>Response:</em> <p>I created the flip coin method within the java server, this allows the<br>client to go ahead and flip a coin. By typing a simple keyword:<br>flip coin the server replies back with either heads or tails. This is<br>done by random number generator (RNG) across all computing platforms. A built-in method<br>random from the math class allows to pick a random number in this<br>case the RNG would be a 0-1, anything below 0.5 would give you<br>&quot;Tails&quot; and anything above would result in heads.<br><br><br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot(s) showing the implemented feature working</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182276213-79591194-550b-4116-9792-d8a1dada00ef.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Code<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Feature Implementation 2 </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> What feature did you pick? Briefly explain how you implemented it</td></tr>
<tr><td> <em>Response:</em> <p>A simple number guesser, allows the client and the server to play guess<br>a number, by the simple process command &quot;Guess&quot;. The server establishes a connection<br>with the client and picks number random, then the client gets a specific<br>number of strikes to guess the number and the server provides user-friendly messages.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot(s) showing the implemented feature working</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/182277139-a582a6d2-c037-4b28-8f40-6b2b70421239.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>Code<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Did you have an issues and how did you resolve them? If no issues, what did you learn during this assignment that you found interesting?</td></tr>
<tr><td> <em>Response:</em> <p>I had issues processing commands, seeing that in the server java files each<br>feature is implemented by a process command code, therefore the flip coinn was<br>implemented in it&#39;s separate process command line. I found it interesting that this<br>can be coding and it&#39;s used often in the real world, a lot<br>of times when you are with your friends and you need to decide<br>in something you would flip a coin. Now you can use Siri or<br>other AI that can do it for you. by use of coding/programming and<br>automation.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Pull request link</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/yaheyaelsaid20/IT114-Summer/pull/4">https://github.com/yaheyaelsaid20/IT114-Summer/pull/4</a> </td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-450-M22/it114-sockets-part-1-3/grade/yre2" target="_blank">Grading</a></td></tr></table>