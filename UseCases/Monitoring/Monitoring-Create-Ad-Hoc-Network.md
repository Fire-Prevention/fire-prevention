# Monitoring Create Ad Hoc Network

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the system using the equipment (drones) to create an ad hoc network for communication with civilians and personnel, in case of communication loss. It starts when there is a prediction for communication loss and ends when the ad hoc network is established and details are sent to the civilians and personnel in the area.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>System</li>
          <li>Drones</li>
          <li>Smartphones</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>Communication loss is predicted while there is an ongoing fire incident</li>
          <li>The drones are located near the damaged communication infrastructure</li>
          <li>Civilians have smartphone devices that can connect to the network</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>The drones act as the antennae for the smartphones to connect</li>
          <li>The smartphones auto-connect to the ad hoc network because it is the only one available</li>
          <li>The system send alerts and details through the ad hoc network(prompting people to inform other people to connect to the network if it hasn't occured automatically)</li>
          <li>Smartphones receive the alerts and communications are established</li>
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
        The ad hoc network is established and communications are temporarily restored in the affected area.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>There are many things that can go wrong with the network connectivity, alternative flows should be examined by someone with more technical knowledge.</td>
  </tr>
<table>
