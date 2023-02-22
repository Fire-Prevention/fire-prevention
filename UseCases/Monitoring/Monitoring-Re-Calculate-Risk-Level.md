# Monitoring Re-Calculate Risk Level

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the system calculating the risk score for each region of the map once an ignition has been verified. It starts when new data from the occuring fire are fed to the simulation and ends when the new score is calculated. The process repeats until the conditions stabilise (the fire is extinguished).
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
          <li>A verified ignition has occured</li>
          <li>The input data is enough to consider the output reliable</li>
          <li>The system has predicted the fire's propagation with satisfactory reliability</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>The simulation is running to predict the fire's propagation for the next time period</li>
          <li>For each region of the map a risk score is calculated</li>
          <li>The risk score is stored in the appropriate field</li>
          <li>The risk score update is logged into a file</li>
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
        The risk score of each region exists and can be displayed through the Risk Heat Map Use Case. The difference between this and the Prevention's use case is that the data are being collected in real time and so the map is updated in real time to assist decision making.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>For now store results is part of this use case. This might go into the shared folder too.</td>
  </tr>
<table>
