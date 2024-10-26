# Go Path Lookup Utility

A minimal Go program that finds the full path of an executable in the `PATH` environment variable, similar to the UNIX `which` command.

**Learning Tip**: Implementing simple UNIX tools is a great way to learn Go.

## Usage

Run:
```bash
go run main.go <filename>
```

Example:
```bash
go run main.go ls
```

If <filename> is found and executable, the program prints its full path.
