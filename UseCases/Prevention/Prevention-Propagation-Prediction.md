# Prevention Propagation Prediction

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the simulation that predicts the propagation of the fire. It starts when the user starts the simulation and ends when the results are produced.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>System</li>
          <li>User</li>
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
          <li>User starts the simulation by setting some parameters</li>
          <li>Simulation runs</li>
          <li>Results are produced</li>
          <li>Continue to Calculate Risk Use Case</li>
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
      3c. <ol type="I">
        <li>Continue to Time-to-arrival Prediction Use Case</li>
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
    <td>Opposed to the Monitoring version of this case, this simulation is for hypothetical fires, and acts more as "training" (we cant ML with the simulations results but we can store them). As a result, these simulations take a lot more time as they run many times for many different points of ignition. Also acts as umbrella for the different features that take the prediction as input to produce other data.</td>
  </tr>
<table>
