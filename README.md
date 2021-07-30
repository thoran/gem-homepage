# gem-homepage

## Description

Open a gem's homepage from the command line.

## Installation

### 0. Have a recent version of Ruby installed

### 1. Clone this repo
```bash
  git clone https://github.com/thoran/gem-hompepage
```
### 2. Copy gem-homepage somewhere in the PATH
```bash
  cp ./gem-homepage/bin/gem-homepage to your preferred executable path
```
### 3. Ensure that the file is executable
```bash
  chmod +x /path/to/gem-homepage
```

## Usage

```bash
  $ gem-homepage gem_name
```

## Notes/Limitations/Ideal Usage

1. It would be nice if the gem command enabled sub-commands in the same way in which git does, such that the following would be possible, but unfortunately is not...
```bash
  $ gem homepage gem_name
```
2. At present (0.0.0) it will open the home pages of any gem which is installed for the current Ruby only, and not for any gem which is not installed for the current Ruby.

## Contributing

1. Fork it ( https://github.com/thoran/gem-homepage/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new pull request
