# Prevention Calculate Risk Levels

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the system calculating the risk score for each region of the map. It starts when a simulation is running and ends when the score is calculated.
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
          <li>The Fire Propagation Simulation model has run at least once</li>
          <li>The input data is enough to consider the output reliable</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>The simulation is running</li>
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
        The risk score of each region exists and can be displayed through the Risk Heat Map Use Case.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>For now store results is part of this use case. This might go into the shared folder too.</td>
  </tr>
<table>
