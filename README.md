
# Go Tutorial

A repo containing all code written following the [Go Tutorial](https://go.dev/doc/tutorial/getting-started).


## Lessons Learned

- Nils
- Multi-variable short hand declaration assignment
- Multi-value return statments
- Error Handling
- Building tests with Go


## Run Locally

Clone the project

```bash
  git clone https://github.com/CStanton-dev/go-tutorial.git
```

Go to the project directory

```bash
  cd go-tutorial
```

Install Go

```bash
  wget -c https://golang.org/dl/go1.18.1.linux-amd64.tar.gz
```

Go to the module directory

```bash
  cd hello
```

Build the module

```bash
  go build
```

Locate build path

```bash
  go list -f '{{.Target}}'
```

Add the Go install directory to your system's shell path.
```bash
  export PATH=$PATH:/path/to/your/install/directory
```

Install the package
```bash
  go install
```

Verify the package runs by typing the name of the package in your systems shell

