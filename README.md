# vagrant-ansible

Project to focus on developping ansible role with vagrant

## Installation

```bash
brew cask install virtualbox
brew cask install vagrant
brew install ansible
```

## Usage

```vagrant
vagrant up
vagrant ssh
```
Ansible playbook is run at vm creation. You can modify it and execute again with vagrant provision. You can ssh on the VM to check 
if the ansible playbook do the job maybe even extract to create a ansible role.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)