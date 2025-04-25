# cs2109s-mini-project-breakthrough-game-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs2109s-mini-project-breakthrough-game-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;102427&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2109S Mini Project: Breakthrough Game Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<p style="text-align: left;"><span style="font-size: 2em;">Overview</span>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<strong>Breakthrough</strong>&nbsp;was the winner of the 2001 8 × 8 Game Design Competition, sponsored by&nbsp;<em>About.com</em>&nbsp;and&nbsp;<em>Abstract Games Magazine</em>. When Dan Troyka formulated it, it was originally for a 7×7 board. We’re going to play it on a 6×6 board to limit the complexity. In terms of our terminology for the agent environment, Breakthrough is a fully observable, strategic, deterministic game. The game always results in a win for one of the two players. So what are you going to do? You are going to play the game of Breakthrough – not as yourself but through the surrogate of your program.

How exactly do you code an AI to play this game? Well, like everything else in this course, we code an agent. An agent takes sensory input and reasons about it, and then outputs an action at each time step. You thus need to create a program that can read in a representation of the board (that’s the input) and output a legal move in Breakthrough. You then need a evaluation function to evaluate how good a board is to your agent. The better your evaluation function, the better your agent will be at picking good moves. You need to put some thought into the structure of your evaluation function.

Aside from the evaluation function, you also need to decide a strategy for exploring the search space. Certainly you can use minimax search but you may want to decide whether you want to use alpha-beta pruning on top of this. You would want to make the best move that you can given the limited time for each move (further provided clarification below).

<strong>Required Files</strong>:

<ul>
<li>template.py: contains code for playing breakthrough between two different game playing agents. Your minimax algorithm will be written in this file.</li>
<li>utils.py: contains some utility functions that can be used directly.</li>
</ul>
<strong>Honour Code</strong>: Note that plagiarism will not be condoned! You may discuss with your classmates and check the internet for references, but you MUST NOT submit code/report that is copied directly from other sources!

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Breakthrough-Technical-Description">Breakthrough Technical Description</h2>
<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/raw.githubusercontent.com/Felo2/mp/68b409d9ce7abb68d941825764a427231dbf2571//imgs/breakthrough_board.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"> Figure 1. Game Board

<pre></pre>
Figure 1 shows our typical game board. Black (<strong>B</strong>) wins by moving one piece to the opposite side, row index 5. White (<strong>W</strong>) wins by moving one piece to row index 0. Kindly&nbsp;<strong>follow the same indexing as provided in&nbsp;<em>Figure 1</em>, and write code only for moving Black</strong>. A simple board inversion will make black’s code work seamlessly for white as well. This technique has been used in the game playing framework of&nbsp;<em>template.py</em>&nbsp;for managing this two player game (the&nbsp;<code>invert_board</code>&nbsp;function is provided in&nbsp;<em>util.py</em>).

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/raw.githubusercontent.com/Felo2/mp/68b409d9ce7abb68d941825764a427231dbf2571//imgs/game_move.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"> Figure 2. Possible Moves

<pre></pre>
Pieces move one space directly forward or diagonally forward, and only capture diagonally forward. The possible moves have been illustrated in&nbsp;<em>Figure 2</em>. In this figure, the black pawn at (3, 2) can go to any of the three spaces indicated forward. The black pawn at (0,4) can either choose to move by going diagonally right or capture by going diagonally left. It cannot move or capture by moving forward; its forward move is blocked by the white pawn. Note that your move is not allowed to take your pawn outside the board.

Your program will always play&nbsp;<strong>black</strong>, whose objective is to move a black pawn to row index 5. Given a move request, your agent should output a pair of coordinates in the form of a pair of one dimensional lists using the coordinate system shown in the figure. For example, for moving the black pawn standing at (0,4) in&nbsp;<em>Figure 2</em>&nbsp;to (1,3), your agent should make a move that returns the two lists: [0, 4] and [1, 3].

Your agent should always provide a legal move. Moves will be validated by the game playing framework provided in&nbsp;<em>template.py</em>. Any illegal moves will result in a decrease in the score of your assignment. If your player makes an illegal move, the competition framework will choose the next available valid move on your behalf. Your agent must always make a move; it is not allowed to skip moves. Your program&nbsp;<em>cannot take more than 3 real-time seconds</em>&nbsp;to make a move. If your program does not output a coordinate within 3 seconds, it will decrease your assignment score further and the competition framework will choose a random move on your behalf.

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Submission-Details">Submission Details</h2>
<ol>
<li>You will need to submit your code written for&nbsp;<code>make_move()</code>&nbsp;function of&nbsp;<code>PlayerAI</code>&nbsp;class (see&nbsp;<em>template.py</em>) in Coursemology — you will have to write your minimax algorithm with alpha beta pruning here. This function takes the board configuration as its parameter and should return the move to be made by utilizing your designed game playing algorithm based on alpha beta pruning (you are allowed to write as many assisting function as you want).</li>
</ol>
The board configuration is passed as the parameter of the function in the form of a two dimensional list of size 6 × 6 (initially, board configuration will look like&nbsp;<em>Game Board in Figure 1</em>). It is represented as a 2D list containing three types of characters: (1)&nbsp;<code>"W"</code>&nbsp;for denoting white pawns, (2)&nbsp;<code>"B"</code>&nbsp;for denoting black pawns, and (3)&nbsp;<code>"_"</code>&nbsp;for denoting empty cells. The move to be made has to be returned in the form of two lists (source position of move, destination position of move). For example, if your function returns [0,4], [1,3], that means the black pawn will move from position [0,4] to [1,3].

<ol start="2">
<li>Apart from your code implementation, you should also wrote a report to let us know the thought process behind your solution. Take this opportunity to convince your grader that you have understood the concepts taught in class and are able to apply it. Your response should include any information you want the grader to know about your submission (see text response question in coursemology). This includes, but is not limited to, descriptions of:</li>
</ol>
<ol>
<li>your algorithms implemented,</li>
<li>your data structures used,</li>
<li>your evaluation function(s)</li>
</ol>
Your grader should be able to understand everything about your solution from reading this response. That said, your code will also be analyzed for correctness and consistency. Note that&nbsp;<strong>the report is expected to be (on average) 2-3 pages worth of report on an A4 word document</strong>.This mini-project is a journey and not just a destination. Our hope is that you will try out different things to make your agent better. Instead of only documenting your final solution, you would also be given credit for describing the approaches that did not quite work.

It is okay to try something and fail. The key is to understand why.

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Provided-Utility-Functions">Provided Utility Functions</h2>
You can use the functions provided in&nbsp;<em>util.py</em>&nbsp;file as you see fit. These functions have mainly been used by the game playing framework in&nbsp;<em>template.py</em>&nbsp;to facilitate the two player game. A short description of these functions is given below:

<ul>
<li><code>generate_init_state()</code>: It generates initial state (<em>Game Board in Figure 1</em>) at the start of the game.</li>
<li><code>print_state(board)</code>: It takes in the board 2D list as parameter and prints out the current state of the board in a convenient way (sample shown in&nbsp;<em>Possible Moves in Figure 2</em>).</li>
<li><code>is_game_over(board)</code>: Given a board configuration, it returns&nbsp;<code>True</code>&nbsp;if the game is over,&nbsp;<code>False</code>&nbsp;otherwise.</li>
<li><code>is_valid_move(board, src, dst)</code>: It takes in the board configuration and the move source and move destination as its parameters. It returns&nbsp;<code>True</code>&nbsp;if the move is valid and returns&nbsp;<code>False</code>&nbsp;if the move is invalid.</li>
<li><code>state_change(curr_board, src, dst, in_place=True)</code>: Given a board configuration and a move source and move destination, this function changes board configuration in accordance to the indicated move.</li>
<li><code>generate_rand_move(board)</code>: It takes in the board configuration as its parameter and generates an arbitrary valid move in the form of two lists. You likely won’t need to use this function. This function is used by the game playing framework in one of two cases – (1) an invalid move has been made by the game playing agent or, (2) the game playing agent has taken more than 3 seconds to make its move. This function updates the board configuration by modifying existing values if&nbsp;<code>in_place</code>&nbsp;is set to&nbsp;<code>True</code>, or creating a new board with updated values if&nbsp;<code>in_place</code>&nbsp;is set to&nbsp;<code>False</code>.</li>
<li><code>invert_board(curr_board, in_place=True)</code>: It takes in the board 2D list as parameter and returns the inverted board. You should always code for black, not for white. The game playing agent in&nbsp;<em>main.py</em>&nbsp;has to make move for both black and white using only black’s code. So, when it is time for white to make its move, we invert the board using this function to see everything from white side’s perspective (done by inverting the colors of each pawn and by modifying the row indices). An example of inversion has been shown in&nbsp;<em>Figure 3 Board Inversion Illustration</em>&nbsp;later. In your minimax algorithm, you need to consider both black and white alternatively. Instead of writing the same code twice separately for black and white, you can use&nbsp;<code>invert_board()</code>&nbsp;function to invert your board configuration that enables you to utilize black’s codes for white pawns as well. That is enough for hints, I guess. This function inverts the board by modifying existing values if&nbsp;<code>in_place</code>&nbsp;is set to&nbsp;<code>True</code>, or creating a new board with updated values if&nbsp;<code>in_place</code>&nbsp;is set to&nbsp;<code>False</code>.</li>
</ul>
Other functions are used to play the game or test your solution. You don’t need to use those functions when you implement your&nbsp;<code>PlayerAI</code>.

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Testing-Your-Game-Playing-Agent">Testing Your Game Playing Agent</h2>
Fill in&nbsp;<code>make_move(board)</code>&nbsp;method of the&nbsp;<code>PlayerAI</code>&nbsp;class with your game playing agent code (you can write as many assisting function as you deem fit). The&nbsp;<code>PlayerNaive</code>&nbsp;class has been provided for you to test out your agent against another program. Always code for Black (assume Black as max player) in both these class functions. The game playing framework calls the&nbsp;<code>make_move(board)</code>&nbsp;method of each agent alternatively. After you complete&nbsp;<code>PlayerAI</code>, simply run the&nbsp;<em>template.py</em>&nbsp;file. You will see the two agents (<code>PlayerAI</code>&nbsp;and&nbsp;<code>PlayerNaive</code>) playing against each other.

<strong>Always remember to return your move within 3 seconds.</strong>&nbsp;You should check for time passed during every recursive call in minimax algorithm to follow this 3 second rule. Whenever you see that 3 seconds is almost over, immediately return the best move you have at your disposal. That is all the hint I can give you. This is really important because the machine where we will run your code maybe much slower than your local machine.

<img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/raw.githubusercontent.com/Felo2/mp/68b409d9ce7abb68d941825764a427231dbf2571//imgs/invert_board.png?w=980&amp;ssl=1" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"> Figure 3. Board Inversion Illustration

<pre></pre>
You have chance to be innovative mainly in 3 areas – (1) the evaluation function used to evaluate the goodness of a state, (2) effective exploration strategy maintaining the time constraint and (3) modifying the alpha beta pruning algorithm for more efficient search. Ultimately, we shall be playing all the student designed agents against each other. So, it will be a small breakthrough tournament. The top players will get some bonus marks.

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Grading-Guidelines">Grading Guidelines</h2>
This mini-project will constitute 10% of your overall grade for CS2109S. The following is the criteria under which your submission will be graded.

Your code will constitute 60% of this mini-project grade. We look for:

<ul>
<li><strong>Making Valid Moves (5%)</strong>: Ensure your moves are valid and complete every move within 3 seconds to get full marks for this section.</li>
<li><strong>Performance Against Baseline Agent (15%)</strong>: Your submitted agent code will be run against our baby agent and a base agent. You should win all our agents and make less than or equal to 3 random moves to get the full credit for this section.</li>
<li><strong>Algorithm Implementation Check (30%)</strong>: If you implement the minimax algorithms and the alpha beta correctly, you receive these marks irrespective of the performance of your agent.</li>
<li><strong>Evaluation Function Check (10%)</strong>: Remember this is a zero-sum game, so your evaluation function should maximize your probability of winning while minimize other player’s chance of winning.</li>
</ul>
The other 40% will be graded purely based on how well your agent perform against other students’ agents.

<strong>Additional note</strong>: As a non-exhaustive list, you are not allowed to:

<ol>
<li>Change the testing framework / timer</li>
<li>Use python to compile C++ script as this is hardware advantage</li>
<li>Use of multi-process as this is hardware advantage</li>
</ol>
The maximum size of code you can upload is 10MB.Try your best and enjoy!

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Note-for-Windows-users">Note for Windows users</h2>
Note that although the Jupyter notebook should work in Windows, we recommend using WSL to test your code. Here are some instructions to help you install WSL and setup Jupyter notebook. (optional)

<ol>
<li>Open PowerShell or Windows Command Prompt in administrator mode by right-clicking and selecting “Run as administrator”, enter the wsl –install command, then restart your machine. You may find more information about WSL&nbsp;<a href="https://learn.microsoft.com/en-us/windows/wsl/install">here.</a></li>
</ol>
<div class="highlight">
<pre>$ wsl --install
</pre>
</div>
<ol start="2">
<li>Once WSL is installed, look for the Ubuntu app in the Windows Start menu and open it. Although Python comes preinstalled with most of the Linux distributions, it unfortunately doesn’t comes with WSL. So you have to install it manually. To do that write the following commands in the Ubuntu shell:</li>
</ol>
<div class="highlight">
<pre>$ sudo apt update <span class="o">&amp;&amp;</span> upgrade
$ sudo apt install python3 python3-pip ipython3
</pre>
</div>
<ol start="3">
<li>This will install Python 3 in your WSL. To check python version type</li>
</ol>
<div class="highlight">
<pre>$ python3 --version
</pre>
</div>
<ol start="4">
<li>Install Jupyter by typing the following command in your Bash Shell.</li>
</ol>
<div class="highlight">
<pre>$ pip3 install jupyter
</pre>
</div>
<ol start="5">
<li>WSL uses a separate file system from your Windows system. To move files from Windows to WSL, open file explorer and navigate to&nbsp;<code>\\wsl$\Ubuntu\home\&lt;username&gt;</code>. Files stored in this folder will appear in the Linux root directory in WSL.</li>
<li>Move your Mini Project folder into WSL. In the Ubuntu shell, change directory into the Mini Project folder and run the following command:</li>
</ol>
<div class="highlight">
<pre>$ jupyter notebook
</pre>
</div>
<ol start="7">
<li>Jupyter will start a server using the python distribution in WSL. Follow the url to open jupyter notebook in your browser.</li>
</ol>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="CodeMirror cm-s-jupyter">
<div class="highlight hl-ipython3">
<pre><span class="sd">"""</span>
<span class="sd">Make sure to import utils.py provided before proceeding. </span>
<span class="sd">Make good use of the in_place parameters.</span>
<span class="sd">"""</span>

<span class="kn">import</span> <span class="nn">utils</span>
</pre>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Task-1:-Make-Valid-Move-Given-a-Board-Representation">Task 1: Make Valid Move Given a Board Representation</h3>
Input: A board state represented as a 2D list

Output: two 1D lists representing source and destination of your move

Note: Your move has to be valid and it has to be made within 3 seconds

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="CodeMirror cm-s-jupyter">
<div class="highlight hl-ipython3">
<pre><span class="kn">import</span> <span class="nn">time</span>
<span class="kn">import</span> <span class="nn">copy</span>

<span class="k">class</span> <span class="nc">PlayerAI</span><span class="p">:</span>
    <span class="k">def</span> <span class="nf">make_move</span><span class="p">(</span><span class="bp">self</span><span class="p">,</span> <span class="n">board</span><span class="p">):</span>
        <span class="sd">'''</span>
<span class="sd">        This is the function that will be called from main.py</span>
<span class="sd">        Your function should implement a minimax algorithm with </span>
<span class="sd">        alpha beta pruning to select the appropriate move based </span>
<span class="sd">        on the input board state. Play for black.</span>

<span class="sd">        Parameters</span>
<span class="sd">        ----------</span>
<span class="sd">        self: object instance itself, passed in automatically by Python</span>
<span class="sd">        board: 2D list-of-lists</span>
<span class="sd">        Contains characters 'B', 'W', and '_' representing</span>
<span class="sd">        Black pawns, White pawns and empty cells respectively</span>
        
<span class="sd">        Returns</span>
<span class="sd">        -------</span>
<span class="sd">        Two lists of coordinates [row_index, col_index]</span>
<span class="sd">        The first list contains the source position of the Black pawn </span>
<span class="sd">        to be moved, the second list contains the destination position</span>
<span class="sd">        '''</span>
        <span class="c1">################</span>
        <span class="c1"># Starter code #</span>
        <span class="c1">################</span>
        <span class="c1"># TODO: Replace starter code with your AI</span>
        <span class="k">for</span> <span class="n">r</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">board</span><span class="p">)):</span>
            <span class="k">for</span> <span class="n">c</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">board</span><span class="p">[</span><span class="n">r</span><span class="p">])):</span>
                <span class="c1"># check if B can move forward directly</span>
                <span class="k">if</span> <span class="n">board</span><span class="p">[</span><span class="n">r</span><span class="p">][</span><span class="n">c</span><span class="p">]</span> <span class="o">==</span> <span class="s1">'B'</span> <span class="ow">and</span> <span class="n">board</span><span class="p">[</span><span class="n">r</span><span class="o">+</span><span class="mi">1</span><span class="p">][</span><span class="n">c</span><span class="p">]</span> <span class="o">==</span> <span class="s1">'_'</span><span class="p">:</span>
                    <span class="n">src</span> <span class="o">=</span> <span class="p">[</span><span class="n">r</span><span class="p">,</span> <span class="n">c</span><span class="p">]</span>
                    <span class="n">dst</span> <span class="o">=</span> <span class="p">[</span><span class="n">r</span><span class="o">+</span><span class="mi">1</span><span class="p">,</span> <span class="n">c</span><span class="p">]</span>
                    <span class="k">return</span> <span class="n">src</span><span class="p">,</span> <span class="n">dst</span> <span class="c1"># valid move</span>
        <span class="k">return</span> <span class="p">[</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">],</span> <span class="p">[</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">]</span> <span class="c1"># invalid move</span>

<span class="k">class</span> <span class="nc">PlayerNaive</span><span class="p">:</span>
    <span class="sd">''' A naive agent that will always return the first available valid move '''</span>
    <span class="k">def</span> <span class="nf">make_move</span><span class="p">(</span><span class="bp">self</span><span class="p">,</span> <span class="n">board</span><span class="p">):</span>
        <span class="k">return</span> <span class="n">utils</span><span class="o">.</span><span class="n">generate_rand_move</span><span class="p">(</span><span class="n">board</span><span class="p">)</span>


<span class="c1">##########################</span>
<span class="c1"># Game playing framework #</span>
<span class="c1">##########################</span>
<span class="k">if</span> <span class="vm">__name__</span> <span class="o">==</span> <span class="s2">"__main__"</span><span class="p">:</span>

    <span class="c1"># public test case 1 (Question 1)</span>
    <span class="n">res1</span> <span class="o">=</span> <span class="n">utils</span><span class="o">.</span><span class="n">test</span><span class="p">([[</span><span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">]],</span> <span class="n">PlayerAI</span><span class="p">())</span>
    <span class="k">assert</span><span class="p">(</span><span class="n">res1</span> <span class="o">==</span> <span class="kc">True</span><span class="p">)</span>

    <span class="c1"># public test case 2 (Question 1)</span>
    <span class="n">res2</span> <span class="o">=</span> <span class="n">utils</span><span class="o">.</span><span class="n">test</span><span class="p">([[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">]],</span> <span class="n">PlayerAI</span><span class="p">())</span>
    <span class="k">assert</span><span class="p">(</span><span class="n">res2</span> <span class="o">==</span> <span class="kc">True</span><span class="p">)</span>

    <span class="c1"># public test case 3 (Question 1)</span>
    <span class="n">res3</span> <span class="o">=</span> <span class="n">utils</span><span class="o">.</span><span class="n">test</span><span class="p">([[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'B'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">],</span> <span class="p">[</span><span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'_'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">,</span> <span class="s1">'W'</span><span class="p">]],</span> <span class="n">PlayerAI</span><span class="p">())</span>
    <span class="k">assert</span><span class="p">(</span><span class="n">res3</span> <span class="o">==</span> <span class="kc">True</span><span class="p">)</span>

    <span class="c1"># template code for Question 2 and Question 3</span>
    <span class="c1"># generates initial board</span>
    <span class="n">board</span> <span class="o">=</span> <span class="n">utils</span><span class="o">.</span><span class="n">generate_init_state</span><span class="p">()</span>
    <span class="c1"># game play</span>
    <span class="n">res</span> <span class="o">=</span> <span class="n">utils</span><span class="o">.</span><span class="n">play</span><span class="p">(</span><span class="n">PlayerAI</span><span class="p">(),</span> <span class="n">PlayerNaive</span><span class="p">(),</span> <span class="n">board</span><span class="p">)</span> <span class="c1"># PlayerNaive() will be replaced by a baby agent in Question 2, or a base agent in Question 3</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">res</span><span class="p">)</span> <span class="c1"># BLACK wins means your agent wins. Passing the test case on Coursemology means your agent wins.</span>
</pre>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="Task-2:-Report">Task 2: Report</h3>
Describe your implemented algorithm, data structure, evaluation function and any other information that you want the grader to know about. Write your response in the coursemology textbox, or paste it there after you are done writing.

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt"></div>
<div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h1 id="Submission">Submission</h1>
Once you are done, please submit your work to Coursemology, by copying the right snippets of code into the corresponding box that says ‘Your answer’, and click ‘Save’. After you save, you can make changes to your submission.

<strong>Additional note</strong>: Please read the detailed submissions instructions under Coursemology question description. The first three questions requires you to&nbsp;<strong>paste the exact same code.</strong>&nbsp;The difference is that the first question test on whether your agent make a&nbsp;<strong>valid</strong>&nbsp;move&nbsp;<strong>within</strong>&nbsp;the given time limit. The second question and third question are playing the actual game against our agents.&nbsp;<strong>Note that each public test case can take a maximum of 5 minutes to complete, and you have maximum 20 attempts for question 2 and 3 respectively.</strong>

Once you are satisfied with what you have uploaded, click ‘Finalize submission.’&nbsp;<strong>Note that once your submission is finalized, it is considered to be submitted for grading and cannot be changed</strong>. If you need to undo this action, you will have to email your assigned tutor for help. Please do not finalize your submission until you are sure that you want to submit your solutions for grading.

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="CodeMirror cm-s-jupyter">
<div class="highlight hl-ipython3">
<pre><span class="nb">print</span><span class="p">(</span><span class="s2">"Hello KorKor"</span><span class="p">)</span>
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser"></div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>Hello KorKor
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[3]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="CodeMirror cm-s-jupyter">
<div class="highlight hl-ipython3">
<pre><span class="nb">print</span><span class="p">(</span><span class="s2">"KorKor naughty"</span><span class="p">)</span>
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser"></div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>KorKor naughty
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[5]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="CodeMirror cm-s-jupyter">
<div class="highlight hl-ipython3">
<pre><span class="nb">print</span><span class="p">(</span><span class="s2">"tietie KorKor"</span><span class="p">)</span>
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser"></div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>tietie KorKor
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[6]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="CodeMirror cm-s-jupyter">
<div class="highlight hl-ipython3">
<pre><span class="nb">print</span><span class="p">(</span><span class="s2">"贴贴KorKor"</span><span class="p">)</span>
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser"></div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>贴贴KorKor
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser"></div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="CodeMirror cm-s-jupyter">
<div class="highlight hl-ipython3">
<pre></pre>
</div>
</div>
</div>
</div>
</div>
</div>
