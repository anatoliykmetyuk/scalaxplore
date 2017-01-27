A set of bash scripts to help searching the Scala code base. Examples (to be invoked from command line):

```bash
def main  # Find the main method of the project
ent Foo   # Find object, trait or class named `Foo`
ext Bar   # Find all subclasses of `Bar`
pkg foo   # Find all the sources in the `foo` package
```

## Usage
Clone this repository and add the path to it to your `PATH` environmental variable.

After you've added the repository to your `PATH`, the scripts from it will be available for execution from command line. Invoke them from the directory you want to search through.
