# CS411-project
<h1> Project Description: </h1>
<p1>We will combine the weather API and the Spotify API in order to make an application that allows the user to receive a playlist from Spotify to match the weather. 
  We expect to use the weather API, and the Spotify API. 
  We will use the database to store user account information.
  We intend to use React.js and Flask, but that may change.
</p1>

<h1>Project Requirements:</h1>
<p1>
<ul>
  <li><b>Goal:</b> Create an easy to use web-interface that allows me to generate a Spotify
playlist corresponding to the local weather.</li>
  <li><b>Non-Goal:</b> : Dynamically / intelligently convert a weather into a matching
playlist seed. </li>
  <li><b>Non-Functional Requirement 1: Security</b>
  <ul> 
    <li>Use OAuth authentication to log into Spotify</li>
    <li>Securely store OpenWeatherMap API keys in local files only without exposing them on GitHub/the web</li>
  </ul></li>
  <li><b>Non-Functional Requirement 2: Fault tolerace</b>
    <ul> 
    <li>Minimize crashes and errors caused from large amounts of matching playlists
</li>
    <li>Ensure the application still responds quickly and accurately when requesting a lot of different playlists from spotify</li>
  </ul></li>
</ul></p1>

<h1>Project Management:</h1>
<ul>
<li><b>Theme:</b> Create a sense of enjoyment and preparation for the day through connecting outside weather forces to music.</li>
<li><b>Epic:</b> Weather based playlists recommendations</li>
<li><b>User Story 1:</b> As a user, I want to ensure that my Spotify account will not lose any of my own data when merging with another website.
<ul>
<li><b>Task:</b> Eliminate data migration while combining different APIs
<ul>
<li><b>Ticket 1:</b> Selectively share and migrate essential data necessary for the merged functionality avoiding transference of information that is not directly relevant to the user experience on the other website.</li>
<li><b>Ticket 2:</b> Initialize a data backup before the merge to serve as a safety net in case anything goes wrong during the migration process, reducing the risk of data loss.</li>
</ul>
</li>
</ul>
</li>
<li><b>User Story 2:</b> As a person who likes variety, I want to be able to have a lot of options from the playlists generated by the weather.
<ul>
<li><b>Task:</b> Ensure a large amount of data can be processed smoothly
<ul>
<li><b>Ticket 1:</b> Use a DB that has capacity to store large amounts of data in an efficient way</li>
<li><b>Ticket 2:</b> Create some kind of filtering system that keeps out playlists that would not fit the correct category to ensure no unnecessary data gets through</li>
</ul>
</li></ul>
</li>
