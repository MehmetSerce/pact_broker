# Can I Deploy Badge

Allowed methods: `GET`

Path: `/pacticipants/{pacticipant}/latest-version/{tag}/can-i-deploy/to/{environmentTag}/badge`

Returns a status badge that can be displayed in a README file that indicates whether the specified version of a pacticipant can be deployed to the specified environment.

To set a custom label for the badge, set the `label` query parameter. eg `?label=my+custom+label+here`.
