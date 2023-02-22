# Monitoring Map Population Distribution

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of the system using the data from the cell phone detection mission to create a map of the distribution of civilians in the affected area. It starts when the data becomes available to the system and ends when the map is displayed.
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
          <li>The data from the cell phone detection is available to the system</li>
          <li>The user is at View Map Screen</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>The System receives the coordinates</li>
          <li>The System creates a filter (overlay) to the map view with icons that correspond to cell phones</li>
          <li>The System creates a Map View (heatmap) to display areas with big civillian concentration</li>
          <li>The System displays the filter by default</li>
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
        The user is able to have an estimated view of where the most civilians are located.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>It will feed the locations to the map view as coordinates, then it can be displayed either as a filter (overlay) with pins or as a heatmap</td>
  </tr>
<table>
