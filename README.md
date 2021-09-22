[![MBARI](https://www.mbari.org/wp-content/uploads/2014/11/logo-mbari-3b.png)](http://www.mbari.org)

# About

This repository contains calibration information and tutorials about hydrophones currently deployed in the MARS network for the [Soundscape Project](https://www.mbari.org/mars-hydrophone/).


## Documentation

See [pacific-sound](http://docs.mbari.org/pacific-sound) for official documentation on installation and for live demos of these tutorial notebooks.

If you are viewing this in github, please note that this is a mirror of the official repository at https://bitbucket.org/mbari/pacific-sound.

## Developer Notes

###  Add notebook filtering

To filter output from any added notebooks, issue this command. Note that this only needed once after the repository is cloned.

```shell
git config --local include.path .gitconfig
```

### Cleaning

To clean the artifacts generated by the notebooks, first, try a dry-run with:

```shell
git clean -fn
```

then to finally clean

```shell
git clean
```

