# Filefile

Filefile is a file used to keep track of all the files you have in your repository’s root directory that end in `file`.

## Wait, what?

The root directories of countless projects across the interwebs are littered with equally countless Filefiles. I find this somewhat entertaining, because it’s inherently obvious that they’re all files.

## What should go in your Filefile

Here is what your average project’s `Filefile` might look like:

```
Berksfile
Blakefile
Cakefile
Cheffile
Filefile
Gemfile
Guardfile
Knylefile
Makefile
Procfile
Rakefile
Tenderfile
Vagrantfile
```

Yes, your Filefile should include itself. Deal with it.

## Creating your very own Filefile

```
$ cd /path/to/your/project
$ touch Filefile && ls *file >> Filefile
```

## Example repositories

- [cobyism/Filefile](https://github.com/cobyism/Filefile/blob/master/Filefile)

## Contributing

Know a variety of Filefile not listed above? Know a repository that has a Filefile? Pull requests are welcome.
