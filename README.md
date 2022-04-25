# Roarum

Roarum is a web forum.


## Scripts

**REQUIREMENTS:** The scripts in this repository depend on **Docker**.

### Build the application

```sh
# Build the application
./script/build
```

### Start the application

```sh
# Start the application
./script/start

# View in browser
open http://localhost:3000/
```

### View the logs

```sh
# View the app logs
./script/log app

# View the database logs
./script/log db
```

### Run tests and audits

```sh
# Run the specs
./script/test

# Run a specific spec
./script/test test/models/comment_test.rb:23

# Run audits and checks
./script/check
```

### Run commands

```sh
# Shell commands must be quoted
./script/sh 'ls -alh'
./script/sh 'ls -alh | grep yml'

# Start interactive bash shell
./script/bash

# Start the rails console
./script/rails c
```

### Stop the application

```sh
# Stop the application
./script/stop
```

### Tear down the application

```sh
# Tear down the application
./script/destroy
```
