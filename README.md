# <p align="center" width="100%"> <img src="./logo.png" width="250" height="250"> </p>

# <p align="center" width="100%"> Slack Web API OIH Connector </p>

## Description

[![Generic badge](https://img.shields.io/badge/Status-NotTested!-lightgrey.svg)](https://shields.io/)

A generated OIH connector for the Slack Web API API (version 1.7.0).

Generated from: https://raw.githubusercontent.com/slackapi/slack-api-specs/master/web-api/slack_web_openapi_v2.json<br/>
Generated at: 2021-05-31T11:08:25+02:00

## API Description

One way to interact with the Slack platform is its HTTP RPC-based Web API, a collection of methods requiring OAuth 2.0-based user, bot, or workspace tokens blessed with related OAuth scopes.<br/>

## Authorization

Supported authorization schemes:

- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:

- `OAUTH_CLIENT_ID` - your OAuth client id
- `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### admin_apps_approve

> Approve an app for installation on a workspace.<br/>

_Tags:_ `admin.apps` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.apps:write`<br/>

### admin_apps_restrict

> Restrict an app for installation on a workspace.<br/>

_Tags:_ `admin.apps` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.apps:write`<br/>

### admin_conversations_archive

> Archive a public or private channel.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_convertToPrivate

> Convert a public channel to a private channel.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_create

> Create a public or private channel-based conversation.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_delete

> Delete a public or private channel.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_disconnectShared

> Disconnect a connected channel from one or more workspaces.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_invite

> Invite a user to a public or private channel.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_rename

> Rename a public or private channel.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_restrictAccess_addGroup

> Add an allowlist of IDP groups for accessing a channel<br/>

_Tags:_ `admin.conversations.restrictAccess` `admin`

### admin_conversations_restrictAccess_removeGroup

> Remove a linked IDP group linked from a private channel<br/>

_Tags:_ `admin.conversations.restrictAccess` `admin`

### admin_conversations_setConversationPrefs

> Set the posting permissions for a public or private channel.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_setTeams

> Set the workspaces in an Enterprise grid org that connect to a public or private channel.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_conversations_unarchive

> Unarchive a public or private channel.<br/>

_Tags:_ `admin.conversations` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.conversations:write`<br/>

### admin_emoji_add

> Add an emoji.<br/>

_Tags:_ `admin.emoji` `admin`

### admin_emoji_addAlias

> Add an emoji alias.<br/>

_Tags:_ `admin.emoji` `admin`

### admin_emoji_remove

> Remove an emoji across an Enterprise Grid organization<br/>

_Tags:_ `admin.emoji` `admin`

### admin_emoji_rename

> Rename an emoji.<br/>

_Tags:_ `admin.emoji` `admin`

### admin_inviteRequests_approve

> Approve a workspace invite request.<br/>

_Tags:_ `admin.inviteRequests` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.invites:write`<br/>

### admin_inviteRequests_deny

> Deny a workspace invite request.<br/>

_Tags:_ `admin.inviteRequests` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.invites:write`<br/>

### admin_teams_create

> Create an Enterprise team.<br/>

_Tags:_ `admin.teams` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.teams:write`<br/>

### admin_teams_settings_setDefaultChannels

> Set the default channels of a workspace.<br/>

_Tags:_ `admin.teams.settings` `admin`

### admin_teams_settings_setDescription

> Set the description of a given workspace.<br/>

_Tags:_ `admin.teams.settings` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.teams:write`<br/>

### admin_teams_settings_setDiscoverability

> An API method that allows admins to set the discoverability of a given workspace<br/>

_Tags:_ `admin.teams.settings` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.teams:write`<br/>

### admin_teams_settings_setIcon

> Sets the icon of a workspace.<br/>

_Tags:_ `admin.teams.settings` `admin`

### admin_teams_settings_setName

> Set the name of a given workspace.<br/>

_Tags:_ `admin.teams.settings` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.teams:write`<br/>

### admin_usergroups_addChannels

> Add one or more default channels to an IDP group.<br/>

_Tags:_ `admin.usergroups` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.usergroups:write`<br/>

### admin_usergroups_addTeams

> Associate one or more default workspaces with an organization-wide IDP group.<br/>

_Tags:_ `admin.usergroups` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.teams:write`<br/>

### admin_usergroups_removeChannels

> Remove one or more default channels from an org-level IDP group (user group).<br/>

_Tags:_ `admin.usergroups` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.usergroups:write`<br/>

### admin_users_assign

> Add an Enterprise user to a workspace.<br/>

_Tags:_ `admin.users` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### admin_users_invite

> Invite a user to a workspace.<br/>

_Tags:_ `admin.users` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### admin_users_remove

> Remove a user from a workspace.<br/>

_Tags:_ `admin.users` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### admin_users_session_invalidate

> Invalidate a single session for a user by session_id<br/>

_Tags:_ `admin.users.session` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### admin_users_session_reset

> Wipes all valid sessions on all devices for a given user<br/>

_Tags:_ `admin.users.session` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### admin_users_setAdmin

> Set an existing guest, regular user, or owner to be an admin user.<br/>

_Tags:_ `admin.users` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### admin_users_setExpiration

> Set an expiration for a guest user<br/>

_Tags:_ `admin.users` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### admin_users_setOwner

> Set an existing guest, regular user, or admin user to be a workspace owner.<br/>

_Tags:_ `admin.users` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### admin_users_setRegular

> Set an existing guest user, admin user, or owner to be a regular user.<br/>

_Tags:_ `admin.users` `admin`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `admin.users:write`<br/>

### calls_add

> Registers a new Call.<br/>

_Tags:_ `calls`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `calls:write`<br/>

### calls_end

> Ends a Call.<br/>

_Tags:_ `calls`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `calls:write`<br/>

### calls_participants_add

> Registers new participants added to a Call.<br/>

_Tags:_ `calls.participants` `calls`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `calls:write`<br/>

### calls_participants_remove

> Registers participants removed from a Call.<br/>

_Tags:_ `calls.participants` `calls`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `calls:write`<br/>

### calls_update

> Updates information about a Call.<br/>

_Tags:_ `calls`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `calls:write`<br/>

### chat_delete

> Deletes a message.<br/>

_Tags:_ `chat`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `chat:write`<br/>

### chat_deleteScheduledMessage

> Deletes a pending scheduled message from the queue.<br/>

_Tags:_ `chat`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `chat:write`<br/>

### chat_meMessage

> Share a me message into a channel.<br/>

_Tags:_ `chat`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `chat:write`<br/>

### chat_postEphemeral

> Sends an ephemeral message to a user in a channel.<br/>

_Tags:_ `chat`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `chat:write`<br/>

### chat_postMessage

> Sends a message to a channel.<br/>

_Tags:_ `chat`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `chat:write`<br/>

### chat_scheduleMessage

> Schedules a message to be sent to a channel.<br/>

_Tags:_ `chat`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `chat:write`<br/>

### chat_unfurl

> Provide custom unfurl behavior for user-posted URLs<br/>

_Tags:_ `chat`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `links:write`<br/>

### chat_update

> Updates a message.<br/>

_Tags:_ `chat`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `chat:write`<br/>

### conversations_archive

> Archives a conversation.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_close

> Closes a direct message or multi-person direct message.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_create

> Initiates a public or private channel-based conversation<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_invite

> Invites users to a channel.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_join

> Joins an existing conversation.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `channels:write`<br/>

### conversations_kick

> Removes a user from a conversation.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_leave

> Leaves a conversation.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_mark

> Sets the read cursor in a channel.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_open

> Opens or resumes a direct message or multi-person direct message.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_rename

> Renames a conversation.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_setPurpose

> Sets the purpose for a conversation.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_setTopic

> Sets the topic for a conversation.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### conversations_unarchive

> Reverses conversation archival.<br/>

_Tags:_ `conversations`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `conversations:write`<br/>

### dnd_endDnd

> Ends the current user's Do Not Disturb session immediately.<br/>

_Tags:_ `dnd`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `dnd:write`<br/>

### dnd_endSnooze

> Ends the current user's snooze mode immediately.<br/>

_Tags:_ `dnd`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `dnd:write`<br/>

### dnd_setSnooze

> Turns on Do Not Disturb mode for the current user, or changes its duration.<br/>

_Tags:_ `dnd`

### files_comments_delete

> Deletes an existing comment on a file.<br/>

_Tags:_ `files.comments` `files`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `files:write:user`<br/>

### files_delete

> Deletes a file.<br/>

_Tags:_ `files`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `files:write:user`<br/>

### files_remote_add

> Adds a file from a remote service<br/>

_Tags:_ `files.remote` `files`

### files_remote_remove

> Remove a remote file.<br/>

_Tags:_ `files.remote` `files`

### files_remote_update

> Updates an existing remote file.<br/>

_Tags:_ `files.remote` `files`

### files_revokePublicURL

> Revokes public/external sharing access for a file<br/>

_Tags:_ `files`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `files:write:user`<br/>

### files_sharedPublicURL

> Enables a file for public/external sharing.<br/>

_Tags:_ `files`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `files:write:user`<br/>

### files_upload

> Uploads or creates a file.<br/>

_Tags:_ `files`

### pins_add

> Pins an item to a channel.<br/>

_Tags:_ `pins`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `pins:write`<br/>

### pins_remove

> Un-pins an item from a channel.<br/>

_Tags:_ `pins`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `pins:write`<br/>

### reactions_add

> Adds a reaction to an item.<br/>

_Tags:_ `reactions`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `reactions:write`<br/>

### reactions_remove

> Removes a reaction from an item.<br/>

_Tags:_ `reactions`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `reactions:write`<br/>

### reminders_add

> Creates a reminder.<br/>

_Tags:_ `reminders`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `reminders:write`<br/>

### reminders_complete

> Marks a reminder as complete.<br/>

_Tags:_ `reminders`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `reminders:write`<br/>

### reminders_delete

> Deletes a reminder.<br/>

_Tags:_ `reminders`

#### Input Parameters

- `token` - _optional_ - Authentication token. Requires scope: `reminders:write`<br/>

### stars_add

> Adds a star to an item.<br/>

_Tags:_ `stars`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `stars:write`<br/>

### stars_remove

> Removes a star from an item.<br/>

_Tags:_ `stars`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `stars:write`<br/>

### usergroups_create

> Create a User Group<br/>

_Tags:_ `usergroups`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `usergroups:write`<br/>

### usergroups_disable

> Disable an existing User Group<br/>

_Tags:_ `usergroups`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `usergroups:write`<br/>

### usergroups_enable

> Enable a User Group<br/>

_Tags:_ `usergroups`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `usergroups:write`<br/>

### usergroups_update

> Update an existing User Group<br/>

_Tags:_ `usergroups`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `usergroups:write`<br/>

### usergroups_users_update

> Update the list of users for a User Group<br/>

_Tags:_ `usergroups.users` `usergroups`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `usergroups:write`<br/>

### users_deletePhoto

> Delete the user profile photo<br/>

_Tags:_ `users`

### users_profile_set

> Set the profile information for a user.<br/>

_Tags:_ `users.profile` `users`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `users.profile:write`<br/>

### users_setActive

> Marked a user as active. Deprecated and non-functional.<br/>

_Tags:_ `users`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `users:write`<br/>

### users_setPhoto

> Set the user profile photo<br/>

_Tags:_ `users`

### users_setPresence

> Manually sets user presence.<br/>

_Tags:_ `users`

#### Input Parameters

- `token` - _required_ - Authentication token. Requires scope: `users:write`<br/>

## License

: slack<br/>
<br/>

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
