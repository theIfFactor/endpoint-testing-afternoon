<img src='assets/Adventure-Display.pdf'
/>
#Endpoints

<b><u>USER ENDPOINTS</u></b>
Get `/api/getUser` 
<br/>
    Returns user data that is on sessions
    <details>
      <summary>Example Output</summary>
    </details>
Get `/api/getAllCharacters/:userId`
<br/>
    Returns all the characters for a user.
    <details>
      <summary>Example Output</summary>
    </details>
Get `/api/getSelectedCharacter/:characterId`
<br/>
    Returns the data for a selected character
    <details>
      <summary>Example Output</summary>
    </details>

<b><u>ENCOUNTER ENDPOINTS</u></b>
Get `/api/getEncounters/:encounterId`
<br/>
    Returns the data for an encounter along with an array of options
    <details>
      <summary>Example Output</summary>
    </details>

<b><u>STORY ENDPOINTS</u></b>
Get `/api/story/:storyId`
<br/>
    Gets the data of a story by id
    <details>
      <summary>Example Output</summary>
    </details>

Get `/api/stories`
<br/>
    Gets the 5 most recent stories
    <details>
      <summary>Example Output</summary>
    </details>

Get `/api/user/stories/:username`
<br/>
    Gets the 5 most recent stories by user
    <details>
      <summary>Example Output</summary>
    </details>

Get `/api/levels/stories/:level`
<br/>
    Gets 5 most recenct stories by level
    <details>
      <summary>Example Output</summary>
    </details>

Get `/api/storyName/:storyName`
<br/>
    Gets 5 most recent stories by name
    <details>
      <summary>Example Output</summary>
    </details>

<b><u>USER  ENDPOINTS</u></b>
Put `api/updateUser`
<br/>
 in body={username} on req.user={userId} (req.session.user for testing)
 <br/>
    Updates the username of the user in the users table
    <details>
      <summary>Example Output</summary>
    </details>
<img src='assets/adventureDB.pdf'
/>