# Postgresql-commands-tutorial
<p>In this tutorial, we will see the list of most commonly used <b>psql commands</b>, which help us to query data from the PostgreSQL database server faster and more effectively.</p>
<p>Firstly we will open the <b>command prompt</b> into our local system and copy the path where we install the PostgreSQL.</p>
<p>Then we will use the below command:</p>
<code><pre>psql -d database -U username -W</pre></code>
<img src="sample images/connect.png" width="450">
<p>Once we write the above command and press the enter key, PostgrSQL will requset user's password.</p>
<img src="sample images/password.png" width="450">
<h4>Switch connection to a new database</h4>
<code><pre>\c database_name</pre></code>
<img src="sample images/database.png" width="450">
<h4>List available databases</h4>
<p>To list all databases in the current PostgreSQL database server, we will use the below command:</p>
<code><pre>\l</pre></code>
<img src="sample images/l.png" width="450">
<h4>List available tables</h4>
<p>To list all tables in the current database, we will use the below command:</p>
<code><pre>\dt</pre></code>
<img src="sample images/dt.png" width="450">
<h4>Describe a table</h4>
<p>The below command is used to describe a table such as a type, column, modifiers of columns, etc.</p>
<code><pre>\d table_name</pre></code>
<img src="sample images/descatable.png" width="450">
<h4>List available functions</h4>
<code><pre>\df</pre></code>
<img src="sample images/function.png" width="450">
<h4>List available schema</h4>
<p>he below command is used to see the available list of all schemas of the currently connected database.</p>
<code><pre>\dn</pre></code>
<img src="sampl images/schema.png">
<h4>List users and their roles</h4>
<p>In psql, we will use the following command to list all users and their assigned roles.</p>                                  
<code><pre>\du</pre></code>                                                                    
<img src="sample images/du.png" width="450">
<h4>List available views</h4>                                           
<p>We will use the following command to get a list of available views in the existing database.</p>                                           
<code><pre>\dv</pre></code>  
<h4>Recover the version</h4>
<p>We will use the version() function in the following command to recover the existing version of the PostgreSQL server.</p>                                     
<code><pre>SELECT version();</pre></code>                                           
<img src="sample images/version.png" width="450">
<h4>Perform the previous command</h4>                                                
<p>We can use the below command to implement the previous command because the following command will help us save our time while we are typing the previous command again.</p>
<code><pre>\g</pre></code>
<img src="sample images/precommand.png" width="450">
<h4>Execute psql commands from a file</h4>                                                   
<p>In case, if we want to implement psql commands from a file, we can use the following command:</p> 
<code><pre>\i filename</pre></code>                                                   
<h4>Get help on psql commands</h4>                                                   
<p>We will use the following command to know all available psql commands.</p>  
<code><pre>\?</pre></code>                                                  
<img src="sample images/help.png" width="450">
<p>And, we can use the below statement to get help on specific PostgreSQL command.</p>                                             
<code><pre>\h</pre></code>
<img src="sample images/h.png" width="450">
<h4>Turn on query execution time</h4>
<p>We will use the following command to turn on query execution time.</p>
<code><pre>\timing</pre></code>
<img src="sample images/timing.png" width="450">                                          
