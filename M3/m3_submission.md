<table><tr><td> <em>Assignment: </em> IT114 - Number Guesser</td></tr>
<tr><td> <em>Student: </em> Yaheya Elsaid(yre2)</td></tr>
<tr><td> <em>Generated: </em> 6/20/2022 1:27:40 AM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-450-M22/it114-number-guesser/grade/yre2" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create the below branch name</li><li>Implement the NumberGuess4 example from the lesson/slides</li><li>Add/commit the files as-is from the lesson material</li><li>Pick 2 of the following options to implement</li><ol><li>Display higher or lower as a hint after a wrong guess</li><li>Implement anti-data tampering of the save file data (reject edits)</li><li>Add a difficulty selector that adjusts the max strikes per level</li><li>Display a cold, warm, hot indicator based on how close to the correct value the guess is (example, 10 numbers away is cold, 5 numbers away is warm, 2 numbers away is hot; adjust these per your preference)</li><li>Add a hint command that can be used once per level and only after 2 strikes have been used that reduces the range around the correct number (i.e., number is 5 and range is initially 1-15, new range could be 3-8 as a hint)</li><li>Implement separate save files based on a "What's your name?" prompt at the start of the game</li></ol><li>Fill in the below deliverables</li><li>Create an m3_submission.md file and fill in the markdown from this tool when you're done</li><li>Git add/commit/push your changes to the HW branch</li><li>Create a pull request to main</li><li>Complete the pull request</li><li>Grab the link to the m3_submission.md from the main branch and submit that direct link to github</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Implementation 1 (one of the picked items) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Two Screenshots: Add a screenshot demonstrating the feature during runtime; Add a screenshot (or so) of the snippets of code that implement the feature</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/174529932-9daaf0b0-4916-4f0a-875b-d955094cb9b8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The Output is working<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/174530139-2a9d900b-43c5-452c-8a24-4473f13c58aa.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The code<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain the logic behind your implementation</td></tr>
<tr><td> <em>Response:</em> <p>The implementation here is displaying higher or lower, using if statements in the<br>process guess method, if a number is higher than guess, it will display<br>higher and lower if the number is less.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Implementation 2 (one of the picked items) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Two Screenshots: Add a screenshot demonstrating the feature during runtime; Add a screenshot (or so) of the snippets of code that implement the feature</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/174529932-9daaf0b0-4916-4f0a-875b-d955094cb9b8.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The output of the code<br></p>
</td></tr>
<tr><td><img width="768px" src="https://user-images.githubusercontent.com/98475508/174530212-b8a001c2-ffe3-429f-b677-2a7a4795db00.png"/></td></tr>
<tr><td> <em>Caption:</em> <p>The code<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain the logic behind your implementation</td></tr>
<tr><td> <em>Response:</em> <p>Using if statements to see if the guess is close to the number<br>generated, first I had used the absolute value number so the difference between<br>the number and the guess is always positive since the guess can be<br>lower than the number which results in a negative value. I chose to<br>use anything more significant than 7 to be cold since the generated number<br>is between 1-10, and cold as 4 since if I do anything else,<br>I will give the user incorrect information because anything more excellent the 4<br>would always be warm, even if it was 7.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="http://via.placeholder.com/400x120/009955/fff?text=Complete"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a link to the related pull request of this hw</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/yaheyaelsaid20/IT114-Summer/pull/3">https://github.com/yaheyaelsaid20/IT114-Summer/pull/3</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Discuss anything you learned during this lesson/hw or any struggles you had</td></tr>
<tr><td> <em>Response:</em> <p>I learned how to implement existing files,&nbsp; at first I thought I had<br>to make new methods to implement, but then&nbsp; I realize if I implement<br>a method it&#39;s much easier. I also remembered that I can use the<br>abs value to always have a positive number, so I can implement the<br>cold and hot implementation. This lesson was very good I used more flow<br>control methods, and allowed me to learn how to conflict with flow control,<br>in this case, I used strictly if statements, rather than else if&#39;s to<br>not allow any conflicts.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-450-M22/it114-number-guesser/grade/yre2" target="_blank">Grading</a></td></tr></table>