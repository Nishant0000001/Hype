<html>
  <head>
    <title>My Music Library</title>
  </head>
  <style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  
  th, td {
    border: 1px solid black;
    padding: 8px;
    text-align: left;
  }
  
  th {
    background-color: #dddddd;
  }
  
  h1 {
    text-align: center;
  }
</style>
  <body>
    <h1>My Music Library</h1>
    <table>
      <tr>
        <th>Title</th>
        <th>Artist</th>
        <th>Album</th>
      </tr>
      <tr>
        <td>Shape of You</td>
        <td>Ed Sheeran</td>
        <td>÷ (Divide)</td>
      </tr>
      <tr>
        <td>Sugar, We're Goin Down</td>
        <td>Fall Out Boy</td>
        <td>From Under The Cork Tree</td>
      </tr>
      <tr>
        <td>Smells Like Teen Spirit</td>
        <td>Nirvana</td>
        <td>Nevermind</td>
      </tr>
    </table>
  </body>
</html>

<script>
  function togglePlaylist() {
    var playlist = document.getElementById("playlist");
    if (playlist.style.display === "none") {
      playlist.style.display = "block";
    } else {
      playlist.style.display = "none";
    }
  }
</script>

