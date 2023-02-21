# Prevention Toggle Map Filters

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of user choosing which filters to show on the map. It starts when the user clicks "Show" or "Hide" on a filter of their choice, and ends when the filter is hidden or shown.
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
          <li>User is at View Map Screen</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>User selects a filter from a list of available filters (houses, traffic, historical monuments, crop fields, forests, etc.)</li>
          <li>User toggles the visibility of the filter on the map by clicking "Hide" or "Show"</li>
          <li>The filter is hidden or shown as an overlay to the map</li>
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
    <td>Multiple filters can be shown simultaneously as opposed to different map views (biodiversity, risk heat map, weather, etc.). Another important difference is that filters are static data that don't change as often as the data on the map views (risk score, biodiversity, weather, etc.).</td>
  </tr>
<table>
