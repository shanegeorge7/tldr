# wishlist

> Manage SSH access and create SSH applications.
> A Charm tool for building SSH-based applications and managing SSH keys.
> More information: <https://github.com/charmbracelet/wishlist>.

- Start the wishlist SSH server:

`wishlist serve`

- Start the server on a specific port:

`wishlist serve --port {{port}}`

- Add a new SSH key:

`wishlist add-key {{path/to/public_key}}`

- List all authorized keys:

`wishlist list-keys`

- Remove an SSH key:

`wishlist remove-key {{key_id}}`

- Display version information:

`wishlist --version`

- Display help:

`wishlist --help`
