**Command Name:**
`a!userdm`

**Bot Response:**
`{a!ae;--title="Message Sent";--color="#000409";--footer="Requested by {user.tag}";--timestamp="true";--description="A message has been sent to {args;1} with the text:\n```{args;2;infinity}```"}
{user.send;{args;2;infinity};{args;1}}`

**Command Description:**
Sends a DM with a message to a user.

**Usage:**
`a!userdm mention message`

**NOTE**: You can also use the user's ID.

**Recommended Settings:**
* Whitelist roles - Staff Team
