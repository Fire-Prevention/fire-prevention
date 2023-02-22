# Monitoring Propagation Prediction

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the simulation that predicts the propagation of the fire. It starts when the ignition is verified as true and ends when the results are produced. It repeats until there is verification that the fire is extinguished.
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
          <li>System has the appropriate data to feed the simulation</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>Parameters are automatically set by the ignition alert</li>
          <li>Simulation runs</li>
          <li>Results are produced</li>
          <li>An image of the most probable propagation is produced and displayed</li>
          <li>The system sends the appropriate alerts through the ad hoc network</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
        3b. <ol type="I">
        <li>Propagation near antenna</li>
        <li>Continue to Communication Loss Predction Use Case</li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        None
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>Use the data from the live feed to predict the course of the fire in the next time period. Also acts as umbrella for the different features that take the prediction as input to produce other data.</td>
  </tr>
<table>
