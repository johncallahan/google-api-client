# Google API Client

A small set of programs to demonstrate a Ruby CLI to the Google Directory API.  Based on [this page](https://developers.google.com/admin-sdk/directory/v1/quickstart/ruby).  Be sure to activate the Directory API and downloads the google_directory_api_credentials.json file before any of the example below.  In each case, you will be asked to cut

# List users

```shell
% ruby users.rb
```

# List groups

```shell
% ruby groups.rb
```

# List group members

```shell
% ruby members.rb group@example.com
```

# Add member to a group

```shell
% ruby users.rb user@example.com group@example.com
```

# Remove member from a group

```shell
% ruby remove_member.rb user@example.com group@example.com
```

# More

[This page](https://www.rubydoc.info/github/google/google-api-ruby-client/Google/Apis/AdminDirectoryV1) was also very helpful.
