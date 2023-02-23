# Personnel Register Use Case

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      This use case allows a user to create a new account in the system. It starts when the user inavigates to the registration page of the system and ends when they are successfuly registered.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>System</li>
          <li>Personnel</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>The user must not already have an account in the system with the same email or username.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>The user navigates to the registration page of the system</li>
          <li>The system displays the registration form, which includes fields for entering the user's name, email, role, and password</li>
          <li>The user enters their name, email, role, and password in the respective fields</li>
          <li>The user clicks on the "Register" button</li>
          <li>The system validates the user's information, checks if the email is not already in use, and creates a new account for the user</li>
          <li>If the validation is successful, the system displays a confirmation message indicating that the registration was successful and prompts the user to log in to their new account</li>
          <li>Continue to Personnel Login use case</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
       5b. <ol type="I">
        <li> If the validation fails, the system displays an error message indicating the reason for the failure and prompts the user to correct the relevant fields</li>
        <li>Continue at step 3</li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        The user is registered in the system and can login using their email and password.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
