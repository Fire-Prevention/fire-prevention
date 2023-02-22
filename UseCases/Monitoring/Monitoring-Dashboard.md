# Monitoring Dashboard

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the dashboard presented to the user once an ignition has been verified and the system is under Monitoring (and Fighting) conditions. It starts when an ignition has been verified as true and ends when the fire has been verified as extinguished.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>User</li>
          <li>System</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>An ignition has been verified as true</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>User is redirected to the Monitoring Dashboard</li>
          <li>User can click on "Configuration" and access the Configuration Use Case</li>
          <li>User can view live feed from any static or deployed equipment available</li>
          <li>Simulation to predict propagation starts automatically once enough data are available (see Propagation Prediction use case)</li>
          <li>User can click to view the Map Views for different Views of the burning area</li>
          <li>User can navigate to Missions Screen to start different missions</li>
          <li>User is prompted to start Data Collection Missions (see Data Collection Mission use case)</li>
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
        None
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>Every new iteration of Dashboard (starting from Prevention will be same as previous plus some features (Rarely minus) so I wont copy all the use cases. I will mention in the Dashboard use case that the button leads to the use case from previous stage. Even better, in the end I will separate the common use cases into a common folder.</td>
  </tr>
<table>
