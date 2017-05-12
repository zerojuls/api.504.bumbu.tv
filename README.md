# api.504.bumbu.tv
A true way RESTful API for famous "504 absolutely essential words" book

<h1>Documentation</h1>
<code>[http://api.504.bumbu.tv/lessons]</code> - will return all available lessons divided by pagination
<code>[http://api.504.bumbu.tv/lessons/1]</code> - will return only the first lesson's data (!WITHOUT WORDS)
<code>[http://api.504.bumbu.tv/lessons/1?expand=words]</code> - will return all words which contain in lesson 1 along with it's data
<code>[http://api.504.bumbu.tv/words]</code> - will return all words available divided by pagination
<code>[http://api.504.bumbu.tv/words/1]</code> - will return only the first word's data 
