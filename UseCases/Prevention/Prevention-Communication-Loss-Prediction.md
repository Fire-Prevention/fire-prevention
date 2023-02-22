# Prevention Communication Loss Prediction

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the system predicting that there will be communication loss in a specific area due to damage to the antenna. It starts when the system  detects propagation near an antenna (of the known infrastructure) and ends when the result is stored.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>System</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>A simulation is already running</li>
          <li>The infrastructure of communications in the area is known to the system</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>Simulation is running</li>
          <li>System detects propagation near an antenna of the infrastructure</li>
          <li>System calculates the risk of losing communication in the area covered by the antenna</li>
          <li>System stores the results</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      None
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        Results of potential risks of communication loss are stored in the system for future reference.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
