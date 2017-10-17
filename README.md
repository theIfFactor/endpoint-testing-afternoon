Endpoints

<b><u>USER ENDPOINTS</u></b>
Get `/api/getUser` 
    Returns user data that is on sessions
Get `/api/getAllCharacters/:userId`
    Returns all the characters for a user.
Get `/api/getSelectedCharacter/:characterId`
    Returns the data for a selected character

<b><u>ENCOUNTER ENDPOINTS</u></b>
Get `/api/getEncounters/:encounterId`
    Returns the data for an encounter along with an array of options

<b><u>STORY ENDPOINTS</u></b>
Get `/api/story/:storyId`
    Gets the data of a story by id

Get `/api/stories`
    Gets the 5 most recent stories

Get `/api/user/stories/:username`
    Gets the 5 most recent stories by user

Get `/api/levels/stories/:level`
    Gets 5 most recenct stories by level

Get `/api/storyName/:storyName`
    Gets 5 most recent stories by name

<b><u>USER  ENDPOINTS</u></b>
Put `api/updateUser` in body={username} on req.user={userId} (req.session.user for testing)
    Updates the username of the user in the users table
