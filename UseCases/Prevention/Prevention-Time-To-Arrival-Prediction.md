# Prevention Time-to-Arrival Prediction

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the system simulating the arrival of the personnel to the fire. It starts when a simulated ignition has occured and ends when the Estimated Time of Arrival has been calculated and stored.
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
          <li>A simulation is running</li>
          <li>The location of each personnel/fire station/fire truck is known to the system and is up to date</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>An ignition occurs in the simulation</li>
          <li>The system simulates the time needed for personnel to arrive to the location of the ignition</li>
          <li>The ETAs are stored for each point of interest (personnel/fire station/fire truck)</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        The ETAs are stored and can be displayed to the user if needed.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
