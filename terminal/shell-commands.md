# Basic shell commands

## `pwd`

1. What does it stand for? Printing Work Directory
2. What does `pwd` do?

### Using `pwd`

1. Show `pwd` command help info

```shell
pwd
```

## `mkdir`

1. What does it stand for? make directory
2. What does `mkdir` do? create a new directory(folder) in the current repo you are in

### Using `mkdir`:

1.  Show `mkdir` command help info

```shell
mkdir folder name
```

2.  Create a directory in your current working directory (`/<current dir/folderOne>`)

```shell
mkdir
```

3.  Create a nested directory in your current working directory (`/<current dir>/fol1/fol2/fol3`)

```shell
<command here>
```

## `cd`

1. What does it stand for? current directory
2. What does `cd` do? see which directory you are one

### Using `cd`:

1. Show `cd` command help

```shell
cd
```

2. Switching into a child directory

```shell
cd child directory
```

3. Switching into the parent directory

```shell
cd parent directory
```

4. Switching to an exact directory (i.e. from `/<home dir>` to `/testing/projects/my-shiny-project`)

```shell
cd /testing/projects/my-shiny-project
```

5. Switching to your home directory from anywhere

   - Method 1 hint: Which common shell environment variable would help here?
   - Method 2 hint: How can you use a tilde (~) with `cd`?

```shell
cd ~$HOME
```

```shell
cd .
```

6. Switching to your root directory from anywhere

```shell
cd ..
```

## `ls`

1. What does it stand for? list
2. What does `ls` do? shows all files/content in current directory

### Using `ls`:

1. Show `ls` command help info

```shell
ls
```

2. List the contents of the current directory

```shell
ls current directory
```

3. List the contents that also shows hidden files in the current directory

```shell
<command here>
```

4. List the contents where directories have the `/` character at the end (displaying the `/` is NOT default behavior across shells, believe it or not)

```shell
<command here>
```

5. List the contents of a directory you're not currently in

```shell
<command here>
```
