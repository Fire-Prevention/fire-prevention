# Monitoring Collect Data Mission

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of equipment (eg. drones) and/or Personnel collecting real time data from the field. It starts when a mission is in progress and end when the data has been sent to the database.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>Personnel</li>
          <li>Database</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>A mission has already started (see Start Mission Use Case)</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>During the mission the personnel and/or equipment (eg. drone) collect an array of real time data (temperature, image, etc.)</li>
          <li>The data is sent to the database to be stored and used by the platforms features</li>
          <li>Mission ends</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      2b. <ol type="I">
        <li>Connectivity issues with the equipment occur</li>
        <li>Personnel is sent to retrieve the equipment for manual extraction of the data?</li>
        <li>End Case</li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        Data is stored to the database which is the closest to real time available to the system.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
