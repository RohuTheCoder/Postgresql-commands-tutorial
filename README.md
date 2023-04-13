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
<img src=sample images/l.png" width="450">
<h4>List available tables</h4>
<p>To list all tables in the current database, we will use the below command:</p>
<code><pre>\dt</pre></code>
<img src="sample images/dt.png" width="450">


