# Monitoring Detect Cell Phones Mission

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of equipment (drones) detecting the cell phones in the area. It starts when the drones start searching for signal from the cell phones and ends when the data is sent to the database.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>Database</li>
          <li>Drones</li>
          <li>User</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>A mission has started to detect the cell phones (see Start Mission use case)</li>
          <li>There is an ongoing fire incident</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>During the mission the drones send out signals to detect cell phones by their response.</li>
          <li>Drones detect signal from a cell phone and save the coordinates of the source</li>
          <li>Drones send the coordinates to the database</li>
          <li>Mission ends</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      2b. <ol type="I">
        <li>No signal detected</li>
        <li>Notify the user</li>
        <li>Continue at step 4</li>
      </ol>
  <tr>
    <td> Post Conditions </td>
    <td>
        The coordinates correspond to the location of a potential civilian, so the system is able to provide the user with a rough estimate of the number and distribution of the civilians in the affected area.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
