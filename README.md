# Filefile

Filefile is a file used to keep track of all the files you have in your repository’s root directory that end in `file`.

## Wait, what?

The root directories of countless projects across the interwebs are littered with equally countless Filefiles. I find this somewhat entertaining, because it’s inherently obvious that they’re all files.

## What should go in your Filefile

Here is what your average project’s `Filefile` might look like:

```
Appfile
Berksfile
Blakefile
Brewfile
buildfile
Caddyfile
Cakefile
Capfile
Caskfile
Cheffile
Dockerfile
Doxyfile
Fastfile
Filefile
Gemfile
Gruntfile
Guardfile
Huxleyfile
Jakefile
Knylefile
Makefile
Modulefile
Podfile
Portfile
Procfile
Puppetfile
Rakefile
Sitefile
Tenderfile
Vagrantfile
Jenkinsfile
```

Yes, your Filefile should include itself. Deal with it.

## Creating your very own Filefile

```
$ cd /path/to/your/project
$ touch Filefile && ls *file >> Filefile
```

## Example repositories

- [cobyism/Filefile](https://github.com/cobyism/Filefile/blob/master/Filefile)
- [pyaa/authority](https://github.com/pyaa/authority/blob/master/Filefile)

## Contributing

Know a variety of Filefile not listed above? Know a repository that has a Filefile? Pull requests are welcome.
