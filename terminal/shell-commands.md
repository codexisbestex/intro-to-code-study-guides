# Basic shell commands

## `pwd`

1. What does it stand for? Print Working Directory
2. What does `pwd` do? tells you the current directory you're in (absolute path)

### Using `pwd`

1. Show `pwd` command help info

```shell
pwd --help
```

2. Show the manual page for `pwd`

```shell
man pwd
```

## `mkdir`

1. What does it stand for? make directory
2. What does `mkdir` do? create a new directory (folder)

### Using `mkdir`:

1.  Show `mkdir` command help info

```shell
mkdir --help
```

2.  Create a directory in your current working directory (`/<current dir>/folderOne`)

```shell
mkdir folderOne
```

3.  Create a nested directory in your current working directory (`/<current dir>/fol1/fol2/fol3`)

```shell
mkdir -p fol1/fol2/fol3
```

## `cd`

1. What does it stand for? change directory
2. What does `cd` do? change from one directory to another

### Using `cd`:

1. Show `cd` command help

```shell
cd --help
```

2. Switching into a child directory, `<cur directory0>/child-dir`

```shell
cd child-dir
```

3. Switching into the parent directory, `<parent-dir>/<cur directory>`

```shell
cd ..
```

4. Switching to an exact directory (i.e. from `/<home dir>` to `<home dir>/testing/projects/my-shiny-project`)

```shell
cd testing/projects/my-shiny-project
```

5. Switching to your home directory from anywhere

   - Method 1 hint: Which common shell environment variable would help here?
   - Method 2 hint: How can you use a tilde (~) with `cd`?

```shell
cd $HOME
```

```shell
cd ~
```

6. Switching to your root directory from anywhere

```shell
cd /
```

or if your root is the C: drive in Windows

```shell
cd /c
# or
cd C:
```

## `ls`

1. What does it stand for? list (directory contents)
2. What does `ls` do? shows all files/content in current directory

### Using `ls`:

1. Show `ls` command help info

```shell
ls --help
```

2. List the contents of the current directory

```shell
ls
```

3. List the contents that also shows hidden files in the current directory

```shell
ls -a
# or
ls -A
```

4. List the contents where directories have the `/` character at the end (displaying the `/` is NOT default behavior across shells, believe it or not)

```shell
ls -F
```

5. List the contents of a directory you're not currently in, `<curr dir>/one/two/three`

```shell
ls one/two/three
```

6. List the contents of the immediate parent directory, `<parentDir (list this)>/<currDir>`

```shell
ls ..
```

7. List the contents of a directory that not a child directory, nor the direct parent, `~/<this dir (list)>/Programming/intro-to-code/<curr dir>`

```shell
ls ~/<this dir>
```
